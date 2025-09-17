AI-Powered Job Recommendation & Career Insights Dashboard
 Project Overview

This project develops an AI-powered system that helps job seekers by:

Providing personalized job recommendations based on resume-to-job semantic matching.

Delivering an interactive dashboard with real-time labor market insights, including in-demand skills, salary benchmarks, and career trajectories.

Unlike traditional job portals (e.g., LinkedIn, Indeed) that rely heavily on keyword matching, our system integrates NLP, ML, and forecasting to provide contextual, personalized, and future-oriented recommendations.

 Team Members

Giridhar Sriram Janga

Sai Bhargav Karnati

Jayanth Rachuri

 Dataset
Glassdoor Job Postings (Primary Dataset)

Source: Scraped biweekly from Glassdoor

Storage: AWS S3 bucket

Current Size: ~1,700 records (Aug 2025)

Growth Rate: +6,000 new listings per month

Attributes: Job Title, Company, Location, Salary Estimate, Company Rating, Job Description

User Resume Dataset

Parsed resumes and portfolios

Extracts skills, experiences, and education

Used for personalized recommendations

🛠 Tech Stack

Languages & Libraries: Python, Pandas, scikit-learn, PyTorch, BERT, Prophet/ARIMA

Data Storage: AWS S3

Dashboard: Tableau / Power BI

Version Control: GitHub

 Project Pipeline

Data Pipeline & Storage

Automated scraper → AWS S3 → Cleaning & Transformation → Historical Records

NLP for Resume–Job Matching

Named Entity Recognition (NER) for skill extraction

Semantic similarity using BERT embeddings + cosine similarity

Baseline: TF-IDF + Logistic Regression

ML Classification & Forecasting

Binary classification for “job fit” prediction

Time-series forecasting (Prophet / ARIMA) for skill demand trends

Interactive Dashboard

Built in Tableau/Power BI

Provides salary trends, skill insights, geographic distribution

 
Evaluation Metrics

Job Matching: Precision@K, Recall@K, F1-score, Cosine Similarity

Forecasting: RMSE, MAE, MAPE

Dashboard: Interpretability, usability feedback
