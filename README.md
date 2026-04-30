# Customer Reviews Sentiment Analysis  
Machine Learning + NLP + Power BI Dashboard

---

## Project Overview

In today’s data-driven environment, customer reviews are a powerful source of business insight. However, extracting meaningful information from large volumes of unstructured text is challenging.

This project builds an end-to-end sentiment analysis pipeline to convert raw customer reviews into actionable business insights using Machine Learning and Business Intelligence tools.

## Business Problem

Organizations struggle to:
- Analyze large volumes of unstructured customer feedback  
- Identify product issues and customer sentiment trends  
- Use customer reviews for decision-making  

This project addresses these challenges by:
- Automating sentiment classification  
- Enabling trend analysis through dashboards  
- Supporting data-driven business decisions  

## Solution Approach

The solution follows a structured analytics pipeline:

### 1. Data Preparation
- Dataset: Amazon Fine Food Reviews (~568K records)  
- Sampled ~100K records for efficient processing  
- Handled missing values and cleaned dataset  

### 2. NLP & Text Processing
- Lowercasing and noise removal  
- Stopword removal (NLTK)  
- Lemmatization  
- Text normalization  

### 3. Feature Engineering
- Sentiment labels (Positive, Neutral, Negative)  
- Review length (word/character count)  
- Helpfulness ratio  
- Time-based features (date, weekend flag)  

### 4. Text Vectorization
- TF-IDF Vectorization (~3000 features)  
- Converts text into numerical format for modeling  

### 5. Model Development
- Algorithm: Logistic Regression  
- Train-Test Split: 80/20  
- Objective: Classify sentiment  

### 6. Model Evaluation

| Metric | Value |
|--------|------|
| Accuracy | 84.56% |
| Training Size | ~80K |
| Testing Size | ~20K |

Key Observations:
- Strong performance on positive sentiment  
- Moderate performance on negative sentiment  
- Weak performance on neutral sentiment due to class imbalance  

## Power BI Dashboard

An interactive dashboard was developed to visualize:

### Sentiment Overview
- Total Reviews: 20K  
- Positive Reviews: ~17K  
- Accuracy: ~85%  

### Model Performance
- Confusion Matrix  
- Correct vs Incorrect Predictions  
- Accuracy by Score  

### Customer Behavior Insights
- Review length vs helpfulness  
- Weekend vs weekday trends  
- Sentiment distribution over time
- 
## Key Business Insights

- Approximately 88% of reviews are positive, indicating high customer satisfaction  
- Longer reviews tend to receive more helpful votes  
- Sentiment trends remain stable over time  
- Positive sentiment correlates with product demand  

## Business Impact

This solution enables:
- Product performance monitoring  
- Demand forecasting support  
- Customer experience improvement  
- Data-driven decision making  

## Tech Stack

- Python: Pandas, NumPy  
- NLP: NLTK  
- Machine Learning: Scikit-learn  
- Visualization: Power BI  

## Limitations & Future Improvements

Limitations:
- Class imbalance (Neutral sentiment underrepresented)  
- Logistic Regression used as baseline model  

Future Enhancements:
- Advanced models (Random Forest, XGBoost, BERT)  
- Class balancing techniques (SMOTE, weighting)  
- Real-time sentiment tracking  
- Integration with business systems  

## Author

Himanshu Chauhan  
Business Analytics | Machine Learning | Power BI  
