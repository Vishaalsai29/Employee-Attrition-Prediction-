# Employee Attrition Prediction (NLP)

## 📌 Project Overview  
This project analyzes employee attrition using **Natural Language Processing (NLP) and Machine Learning** techniques. The objective is to **identify key factors contributing to employee turnover** and build predictive models to assess attrition risks based on employee reviews and structured HR data.

## 🔍 Key Objectives  
- Perform **sentiment analysis** on **2,000+ employee reviews** to uncover **workplace dissatisfaction trends**.  
- Develop **predictive models** to estimate **employee attrition likelihood** based on structured HR data.  
- Provide **actionable insights** for HR management to mitigate turnover risks and improve retention strategies.

## 🗃 Dataset & Preprocessing  
- **Dataset:** IBM HR employee attrition dataset (~1,470 records, 36 features).  
- **Data Distribution:** Highly imbalanced towards **Attrition = No**, requiring resampling techniques.  
- **Feature Engineering:**  
  - **Numerical Features:** TotalWorkingYears, YearsInCurrentRole, YearsAtCompany, etc.  
  - **Categorical Features:** JobRole, MaritalStatus, EducationField, etc.  
  - **Target Variable:** Attrition (Yes/No).  
- **Text Processing for NLP:**  
  - Tokenization, Stopword Removal, Lemmatization using **NLTK** and **Pandas**.  
  - Sentiment analysis to extract **employee dissatisfaction trends**.  

## ⚠️ Key Findings  
| **Factor** | **Impact on Attrition** |  
|------------|------------------------|  
| **Job Role & Growth** | Lack of career progression correlated with higher attrition. |  
| **Work-Life Balance** | Employees citing work-life imbalance showed increased dissatisfaction. |  
| **Management Transparency** | Poor management feedback led to lower retention rates. |  
| **Compensation** | Competitive pay was a **retention factor**, while low raises increased attrition. |  

## 🏆 Model Development & Performance  
### **1️⃣ Sentiment Analysis (NLP-Based Approach)**  
- **Tools Used:** NLTK, Pandas, Seaborn, Matplotlib.  
- **Insights:** Key dissatisfaction drivers were **management issues and unclear growth paths**.  

### **2️⃣ Machine Learning Classifiers**  
- **Logistic Regression, Decision Trees, Random Forest, XGBoost**.  
- **Evaluation Metrics:**  
  - **Accuracy:** Over 80% for all models.  
  - **Recall for Attrition = Yes:** Improved from 15% to **30%** after balancing and feature selection.  
  - **Feature Importance:** Only **10 key features** significantly contributed to attrition prediction.  

## 🎯 Recommendations for HR Strategy  
- Improve **management transparency** and **career progression pathways**.  
- Strengthen **work-life balance policies** to enhance employee satisfaction.  
- Introduce **competitive compensation plans** to retain high-performing employees.  

## 🚀 Conclusion  
This project successfully integrates **structured HR data with NLP-based sentiment analysis** to provide a **data-driven strategy for mitigating employee attrition risks**. Future improvements could involve **deploying an AI-powered attrition prediction tool** using **streaming HR data**.
