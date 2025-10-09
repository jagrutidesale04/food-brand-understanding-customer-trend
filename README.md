# Food Brand Understanding Customer Trends

## Project Overview
Customer feedback is a goldmine for innovation in the food industry. This project focuses on integrating feedback data from surveys, social media, and product reviews into Power BI to generate insights on customer satisfaction, recurring complaints, and emerging preferences. By leveraging sentiment analysis and behavioral clustering, this project supports product, R&D, and marketing teams in making informed decisions.

This project has been completed under the guidance of **Pavithra Kannan Ma'am** as part of **Infosys Springboard Virtual Internship 6.0**, Team 6.

## Team Members & Roles

| Sr No. | Member | Role |
|--------|--------|------|
| 1. | **Jagruti Desale** | Content Creation & Documentation |
| 2. | **Aditya Singh** | Power BI Dashboards Development |
| 3. | **Sanskar Choudhari** | PPT Creation & Presentation Design |

## Dataset
We have used the **Swiggy Restaurant Food Trends Dataset** to analyze customer feedback, ratings, and preferences.

## Project Objectives
- Centralized view of customer sentiment across products and regions
- Visualization of most-liked and most-criticized product features
- Keyword and theme detection from unstructured feedback
- Customer segmentation by satisfaction, frequency, and preferences
- Regional patterns in preferences and complaints
- Actionable strategy recommendations for product innovation and campaigns
- AI-based review scoring and trend detection

## Modules Implemented

### 1. Data Collection & Cleaning
- Import structured (survey) and unstructured (reviews/social) data
- Clean text using tokenization, normalization, and deduplication
- Create unified tables with `user_id`, `product_id`, `sentiment_score`

### 2. Sentiment Analysis Module
- Classify feedback as positive, neutral, or negative using AI/NLP
- Visualize sentiment scores per product, feature, and region
- DAX measures for positive feedback ratio and sentiment changes over time

### 3. Product Insights Module
- Compare product categories by average rating and sentiment
- Visuals for taste, price, packaging, etc.
- Correlation analysis between sales and feedback

### 4. Customer Segmentation
- Identify behavioral personas: **“Loyal Fans”**, **“Critics”**, **“Silent Users”**
- Cluster users based on rating frequency, sentiment, and product preferences
- Filters for region, age, and purchase channel

### 5. Strategy & Innovation Dashboard
- Identify trending keywords and emerging issues
- Highlight opportunity areas for marketing and R&D
- Track sentiment before and after product launches

## Week-wise Module Implementation Plan

| Week | Module | Deliverables |
|------|--------|-------------|
| 1–2  | Data Cleaning & Integration | Cleaned feedback data with structured schema |
| 3–4  | Sentiment Analysis | Feedback classification and sentiment visuals |
| 5–6  | Product Module | Performance dashboard by feature/category |
| 7–8  | Segmentation | Behavioral personas and demographic splits |
| 9–10 | Strategy Layer | Keyword insights, marketing dashboard |

## Evaluation Criteria (Milestone-Based)
- **Milestone 1 (Week 2):** Cleaned and standardized data from surveys, social media, and reviews. Unified data model validated.  
- **Milestone 2 (Week 4):** Sentiment analysis implemented. Dashboard includes sentiment trends and keyword-based feedback themes.  
- **Milestone 3 (Week 6):** Product-level dashboards with category comparisons and sentiment correlation completed.  
- **Milestone 4 (Week 8):** Segmentation and user personas visualized across region and age filters.  
- **Milestone 5 (Week 10):** Final strategy dashboard with trend keywords, sentiment shifts, and actionable recommendations.

## Architecture Diagram
- **Data Sources:** Survey forms, reviews, social media data (CSV/API)  
- **Transformation:** Power Query + optional Python (for NLP)  
- **Semantic Model:** Customer, Product, Feedback, Time dimensions  
- **Dashboard Layer:** Sentiment, Product, and Persona Dashboards

## Power BI Dashboards
We have created dashboards for each milestone to visualize insights from customer feedback, sentiment analysis, product comparisons, and customer segmentation.  

## GitHub Accounts of Team Members
- [Jagruti Desale](https://github.com/jagrutidesale04)  
- [Aditya Singh](https://github.com/7-Aditya)  
- [Sanskar Choudhari](https://github.com/SanskarChoudhari-1)  

---

**Repository Link:** [Food Brand Understanding Customer Trends](https://github.com/jagrutidesale04/food-brand-understanding-customer-trend/tree/main)
