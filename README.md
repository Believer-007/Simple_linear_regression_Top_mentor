#  Simple Linear Regression ML Projects

### **Delivery Time Prediction & Salary Prediction**

This repository contains two supervised ML projects built using **Simple
Linear Regression**. Both follow a complete workflow including **EDA,
visualization, modeling, and evaluation**.

------------------------------------------------------------------------

## Projects Overview

##  **1. Delivery Time Prediction**

Predict Delivery Time based on Sorting Time.

###  **Use Case**

Logistics companies need to estimate delivery times. Sorting time
strongly influences total delivery duration. A simple regression model
helps forecast delivery time efficiently.

###  **Dataset Details**

  Feature         Description
  --------------- -------------------------------
  Sorting Time  :  Time taken to sort items
  Delivery Time  : Time taken for final delivery

###  **Insights**

-   Delivery Time shows slight right skew.\
-   Strong positive correlation between Sorting Time & Delivery Time.\
-   Scatterplot reveals linear trend → suitable for Linear Regression.\
-   No missing values.

###  **Model**

-   **Algorithm:** Linear Regression\
-   **Library:** Scikit-learn\
-   The regression line fits the data well, capturing the upward trend.

###  **Model Performance**

-   **R² Score** -- Strong model fit\
-   **RMSE** -- Low prediction error

------------------------------------------------------------------------

##  **2. Salary Prediction**

Predict Salary based on Years of Experience.

###  **Use Case**

Businesses estimate employee salary expectations using years of
experience. This regression model helps HR teams in budgeting, hiring,
and salary planning.

###  **Dataset Details**

  Feature           Description
  ----------------- ------------------------
  YearsExperience   Number of years worked
  Salary            Annual salary

###  **Insights**

-   Years of Experience and Salary show a nearly perfect linear
    relationship.\
-   Strong correlation validated via heatmap.\
-   Clean dataset with no missing values.

###  **Model**

-   **Algorithm:** Linear Regression\
-   **Library:** Scikit-learn\
-   Model trained on rounded input values for stability.

###  **Evaluation Metrics**

-   **R² Score** -- Very high\
-   **RMSE** -- Low\
-   **MAPE** -- Low percentage error\
    Overall, the model is accurate and reliable.

------------------------------------------------------------------------

#  Tools & Technologies

  Category           Tools
  ------------------ ---------------------------------
  Programming        Python
  Data Handling      Pandas, NumPy
  Visualization      Matplotlib, Seaborn
  Machine Learning   Scikit-learn
  Environment        Jupyter Notebook / Google Colab

------------------------------------------------------------------------

#  Repository Structure

     Simple-Linear-Regression-Projects
    │
    ├── Delivery_Time_Prediction/
    │   ├── delivery_time.csv
    │   ├── Simple LR Delivery prj1.ipynb
    │   └── Graphs/
    │
    ├── Salary_Prediction/
    │   ├── Salary_Data.csv
    │   ├── Simple LR Salary.ipynb
    │   └── Graphs/
    │
    └── README.md


------------------------------------------------------------------------

#  Keywords for GitHub SEO

    machine-learning  
    linear-regression  
    simple-linear-regression  
    salary-prediction  
    delivery-time-prediction  
    python-project  
    sklearn  
    data-visualization  
    ml-beginner-projects  
    regression-analysis  
    predictive-modelling  
    google-colab  

------------------------------------------------------------------------

#  Conclusion

This repository demonstrates the practical application of **Simple
Linear Regression** for solving real-world prediction tasks. Both models
show strong relationships between features and outcomes, proving linear
regression's effectiveness in early-stage ML projects.


