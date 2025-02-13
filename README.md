# 🏋️‍♂️ Predicting Gym Membership Retention Using Machine Learning


## 📌 Project Overview

This project aims to analyze and predict **gym membership retention** at **ABC Gym** using **machine learning techniques**. The gym faces high attrition rates, leading to revenue loss and operational inefficiencies. 


By leveraging **Logistic Regression, Random Forest, and Support Vector Machines (SVMs)**, this project seeks to:

- Identify key factors that influence **customer retention**.

- Develop predictive models to classify members into **"likely to retain"** or **"likely to churn"**.

- Optimize marketing strategies based on insights from the model.


---


## 🎯 Objectives

✅ **Identify Key Predictors** - Find the major factors influencing gym membership retention (e.g., age, income, visit frequency).  

✅ **Develop Predictive Models** - Train **Logistic Regression, Random Forest, and SVM** models to classify membership retention.  

✅ **Evaluate Model Performance** - Compare models using **accuracy, precision, recall, and F1-score**.  

✅ **Provide Actionable Insights** - Help ABC Gym with data-driven **marketing and customer engagement strategies**.  


---


## 📊 Dataset

The dataset consists of **4,000 entries** sourced from **Kaggle**, containing:

- **Demographic Data**: Age, gender, income.

- **Behavioral Data**: Visit frequency, membership duration.

- **Financial Data**: Payment method, membership type.

- **Engagement Data**: Promotional participation, workout time preferences.


**Preprocessing Steps:**

- Handled missing values.

- Scaled numerical features (Min-Max scaling).

- Applied one-hot encoding to categorical variables.

- Removed redundant columns.


---


## 🏗 Methodology


### **1️⃣ Data Preprocessing**

- Checked for **null values and duplicates**.

- Applied **one-hot encoding** for categorical data.

- Scaled numerical features using **Min-Max Scaling**.


### **2️⃣ Exploratory Data Analysis (EDA)**

- Analyzed feature distributions and correlations.

- Identified class imbalance.


### **3️⃣ Model Development**

- **Logistic Regression** 🟢 - Simple, interpretable baseline model.

- **Random Forest** 🌲 - Handles non-linearity and feature interactions.

- **Support Vector Machine (SVM)** 🔺 - Best suited for high-dimensional data.


### **4️⃣ Model Evaluation**

- Compared models using:

  - **Accuracy**

  - **Precision**

  - **Recall**

  - **F1-score**

- Applied **GridSearchCV for hyperparameter tuning**.


---


## 📉 Results & Insights

- **Random Forest** outperformed Logistic Regression with an **F1-score of ~85%**.

- Key factors affecting retention:  

  - **Membership Duration** 📆 - Longer membership correlates with higher retention.  

  - **Visit Frequency** 🏋️ - Members who visit frequently are more likely to stay.  

  - **Promotional Participation** 🎟 - Discounts and incentives improve retention.  


- **Suggested Strategies for ABC Gym:**

  - Offer **personalized retention campaigns** for high-risk members.

  - Introduce **loyalty programs** based on visit frequency.

  - Use **data-driven insights** for **targeted marketing**.


---


## 🛠 Challenges & Solutions

| **Challenge** | **Solution** |

|--------------|-------------|

| Data Imbalance 📉 | Applied **SMOTE (Synthetic Minority Over-sampling Technique)** |

| Feature Selection ❓ | Used **feature importance analysis** to retain only significant predictors |

| Overfitting 🎭 | Applied **cross-validation & hyperparameter tuning** |


---


## 🚀 Future Enhancements

🔹 **Deep Learning Integration** - Explore neural networks for better prediction accuracy.  

🔹 **Real-time Prediction Model** - Deploy as a **web application** for gym owners.  

🔹 **Enhanced Data Collection** - Integrate **user feedback and sentiment analysis**.  


---


## 📜 Acknowledgments

This project was developed as part of the **Interim Progress Demonstration (IPD) for the BSc (Hons) Data Science and Analytics** at the **University of Westminster**.


👨‍🎓 **Student:** Minidu Deveendra Pathirana  

🎓 **Supervisor:** Yasangi Gamage  


---


## 📄 References

1. Semrl, J. and Matei, A. (2017). *Churn prediction model for effective gym customer retention.* [IEEE Xplore](https://doi.org/10.1109/BESC.2017.8256385).

2. Aldosary, M. and Alrashdan, A. *Churn Prediction for Gym Members Using Artificial Neural Networks.* [IEEE](https://www.ieomsociety.org/singapore2021/papers/720.pdf).

3. Rohde, K.I.M. and Verbeke, W. (2017). *We like to see you in the gym—A field experiment on financial incentives for gym attendance.* [Journal of Economic Behavior](https://doi.org/10.1016/j.jebo.2016.12.012).
