# Big Data Analytics: Amazon Reviews Helpfulness Prediction

## 📊 Project Overview
This project analyzes **4.6+ million Amazon Video Games reviews** using Apache Spark and machine learning to predict review helpfulness. The implementation demonstrates a complete big data pipeline from data ingestion to predictive modeling and business insights.

## 🚀 Key Features
- **Large-scale Data Processing**: 4.6M+ reviews processed using PySpark
- **Machine Learning**: Logistic Regression model predicting review helpfulness
- **Business Insights**: Counter-intuitive findings about review quality
- **Scalable Architecture**: Built on Databricks cloud platform

## 📈 Results Summary
- **Model Accuracy**: 76.8%
- **AUC Score**: 0.754
- **Key Insight**: Critical reviews (avg 3.8★) are more helpful than positive ones (avg 4.3★)
- **Verified vs Non-verified**: Non-verified reviews have 46.9% helpful rate vs 21.7% for verified

## 🛠️ Technology Stack
- **Platform**: Databricks on Microsoft Azure
- **Processing**: Apache Spark 3.5.0, PySpark
- **Machine Learning**: Spark MLlib, Scikit-learn
- **Data Format**: JSONL (10GB+ dataset)

## 📁 Project Structure
BDA-Project/
├── BDA_Project.ipynb # Main analysis notebook
├── BDA_Assignment.doc # Complete project report
├── README.md # This file


## 🔧 Implementation Steps

### 1. Data Ingestion & Cleaning
- Loaded 4,624,615 reviews from JSONL format
- Filtered null values and engineered features
- Created review length, helpfulness flags, and categorization

### 2. Exploratory Data Analysis
- Rating distribution analysis (74.5% positive reviews)
- User behavior patterns and product performance
- Verified vs non-verified purchase comparison

### 3. Machine Learning Model
- **Features**: rating, review_length, verified_purchase, word_count
- **Algorithm**: Logistic Regression
- **Target**: is_helpful (binary classification)
- **Performance**: 76.8% accuracy, AUC 0.754

## 💡 Key Business Insights

### Surprising Findings:
1. **Critical reviews are more valuable** than positive ones
2. **Non-verified purchases** provide more helpful content
3. **Review depth matters** more than simple length
4. **Content quality** outweighs verification status

### Recommendations:
- Prioritize critical reviews in ranking algorithms
- Balance verified and non-verified review content
- Encourage detailed, substantive reviews
- Implement automated quality scoring

## 📊 Model Performance
| Metric | Score | Improvement |
|--------|-------|-------------|
| Accuracy | 76.8% | +4.2% over baseline |
| AUC Score | 0.754 | Good discrimination |
| Feature Impact | Strong negative: rating, verified_purchase | |

## 🎯 Business Impact
- **Improved conversion rates** through better review curation
- **Enhanced customer trust** with more relevant content
- **Reduced decision fatigue** for shoppers
- **Data-driven product insights** from critical feedback

## 📚 References
- Chen et al. (2012) - Business Intelligence frameworks
- Zaharia et al. (2016) - Apache Spark architecture
- Mudambi & Schuff (2010) - Review helpfulness determinants

## 👨‍💻 Author
**Prayag Pramod**  
Big Data Analytics Program - 2025

---
*This project demonstrates practical application of big data technologies for solving real-world e-commerce challenges.*
