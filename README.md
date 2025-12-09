# 🚀 SpaceX Falcon 9 Landing Success Prediction  
### IBM Data Science Professional Certificate – Capstone Project  

## 📌 Project Overview  
The goal of this project is to **predict whether the Falcon 9 first stage will successfully land**, a critical factor in reducing launch costs and maintaining SpaceX’s competitive advantage in the space industry.  

Because SpaceX can reuse boosters after a successful landing, the ability to **predict landing outcomes** is valuable for financial planning, mission design, and risk reduction.  

This end-to-end data science project includes:  
- Data collection via API + web scraping  
- Feature engineering & data cleaning  
- Exploratory Data Analysis (EDA)  
- Interactive visual analytics  
- Machine learning model development  
- Model evaluation & insights  

---

## 🎯 Business Problem  
SpaceX markets Falcon 9 launches at **~$62M**, but the actual marginal cost can drop to under **$30M** due to booster reuse.  

Being able to predict landing success helps:  
- Reduce operational risk  
- Improve launch planning  
- Lower mission cost uncertainty  
- Support pricing strategy for customers  

---

## 📂 Dataset  
The dataset includes historic Falcon 9 launches and contains features such as:  
- **Flight Number**  
- **Launch Site**  
- **Orbit Type**  
- **Payload Mass**  
- **Booster Version**  
- **Flight Outcome**  
- **Launch Site Coordinates**  
- **Landing Outcome (Target Variable: Success/Failure)**  

Data sources:  
- SpaceX REST API  
- Web scraping (SpaceX Wikipedia page)  
- Provided CSV datasets from IBM Skills Network

---

## 🔍 Exploratory Data Analysis (EDA)  

Key analytical steps:  

### ⭐ Univariate & Bivariate Analysis  
- Examined landing success rates across launch sites  
- Analyzed payload mass vs. landing outcome  
- Explored orbit type impact on landing probability  
- Investigated booster version patterns  

### ⭐ Geographic Visualization  
- Mapped launch sites & landing locations using Folium  

### ⭐ Interactive Dashboards  
(If included in your version)  
- Created Dash app with launch site filters  
- Displayed payload vs. class scatter plot  
- Showed success rate by launch site  

---

## 🤖 Machine Learning Approach  

### **Models Trained**
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  

### **Feature Engineering**
- Created dummy variables  
- Normalized continuous features  
- Tuned hyperparameters using GridSearchCV  

---

## 🧪 Model Evaluation  

Metrics used:  
- Accuracy Score  
- F1 Score  
- Confusion Matrix  

### **Best Model:**  
> 🎉 The **Decision Tree Classifier** (or whichever performed best in your results) achieved the highest accuracy and balanced performance between precision and recall.

This model effectively captures nonlinear relationships present in the SpaceX launch data.

---

## 📈 Key Insights  

- Launch Site **KSC LC-39A** has one of the highest landing success rates.  
- Heavier payloads slightly reduce the probability of a successful landing.  
- Newer booster versions (e.g., Block 5) drastically improve landing success.  
- Orbits such as **GTO** are more challenging and reduce success probability.  
- Machine learning confirms: **launch site + booster version** are the strongest predictors.  

---

## 💼 Business Recommendations  

### 1️⃣ Optimize Launch Scheduling  
Prioritize launches from sites with proven high success rates to reduce risk.

### 2️⃣ Invest in Booster Technology  
Block 5 and newer boosters significantly outperform earlier versions — continued investment decreases failure rate and cost per launch.

### 3️⃣ Use ML Predictions in Mission Planning  
Integrate this model into SpaceX’s planning workflow to forecast landing success before each mission.

### 4️⃣ Customer Pricing Strategy  
Higher predicted landing probability → lower operational risk → opportunities for more competitive pricing.

---


