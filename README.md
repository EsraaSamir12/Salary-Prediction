# Salary Prediction Project

## 📌 Project Overview
This project aims to predict salaries based on various factors such as job title, experience level, company location, and industry. The model leverages data mining techniques, including data preprocessing, feature engineering, and machine learning algorithms, to generate accurate salary estimations.

## 📊 Dataset
- **Source:**  salary dataset
- **Features:** Includes categorical and numerical variables such as job title, experience level, company size, industry, and salary.
- **Target Variable:** Salary (numerical value)

## 🛠 Data Preprocessing
Handling real-world data comes with challenges. The preprocessing steps include:
1. **Handling Missing Values:**
   - Median and mode imputation for numerical and categorical features, respectively.
2. **Outlier Detection & Removal:**
   - Used the **Interquartile Range (IQR)** method to filter out extreme values.
3. **Handling Duplicates:**
   - Identified and removed duplicate records.
4. **Addressing Inconsistent & Rare Categories:**
   - Grouped infrequent categories using **frequency binning**.

## 🔍 Exploratory Data Analysis (EDA)
- **Distribution Analysis:** Visualized salary distribution.
- **Feature Correlation:** Identified relationships between features and salary.
- **Categorical Encoding:** Applied one-hot encoding and label encoding where necessary.

## 🚀 Model Development
We experimented with multiple regression models to predict salaries:
1. **Linear Regression**
2. **Random Forest Regressor**
3. **Decision Tree Regressor**

### 🏆 Model Evaluation
To assess model performance, we used:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-squared Score (R²)**

## 📈 Visualization
- Salary trends over different experience levels and job roles.
- Salary distribution across industries and company sizes.
- Feature importance ranking.

## 🔧 Tech Stack
- **Programming Language:** Python
- **Libraries Used:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 💡 Key Takeaways
- Data preprocessing plays a crucial role in salary prediction.
- Feature engineering and selection significantly impact model accuracy.
- Decision Tree and Random Forest models performed well for this dataset.

