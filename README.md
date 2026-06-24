# Customer Segmentation & Marketing Campaign Prediction

## 📌 Project Overview
A machine learning project analyzing customer personality data for a retail company. The goal is to segment customers into meaningful groups and predict marketing campaign acceptance.

## 🎯 Objectives
- **Objective 1:** Customer Segmentation using K-Means Clustering
- **Objective 2:** Campaign Prediction using Classification Models

## 📊 Dataset
- 2,240 customers | 29 features
- Features include: demographics, income, spending behavior, campaign responses

## 🛠️ Tools & Technologies
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Project Structure
```
├── marketing_campaign.csv
├── Finalprojectmarketing.ipynb
└── README.md
```

## 🔍 Key Findings
### Customer Segments
| Cluster | Type | Description |
|---------|------|-------------|
| 0 | Low-Value | Low income, low spending, inactive |
| 1 | **High-Value** ⭐ | High income, high spending |
| 2 | Regular | Medium income, medium spending |
| 3 | At-Risk | Low spending, recent activity |

### Model Performance
| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Logistic Regression | 86.61% | 0.40 |
| Decision Tree | 79.69% | 0.33 |
| **Random Forest** ✅ | **86.16%** | **0.42** |

## 💡 Recommendations
1. Focus premium offers on **High-Value customers** (Cluster 1)
2. Re-engage inactive customers **(Cluster 0)** with targeted discounts
3. Prioritize **previous campaign acceptors** for future campaigns
