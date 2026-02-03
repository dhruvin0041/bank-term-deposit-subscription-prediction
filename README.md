📊 Predicting Client Subscription to Term Deposits
🧠 Project Overview

This project focuses on predicting whether a bank client will subscribe to a term deposit using historical marketing campaign data.
We perform exploratory data analysis (EDA), visualize key patterns, preprocess data, and build a Logistic Regression model to make predictions.

The dataset contains demographic details, campaign information, contact methods, and economic indicators that influence client decisions 

Predicting_Client_subscription_…

📁 Dataset Description

The dataset includes the following types of features:

Demographic Information: Age, job, marital status, education

Financial Status: Housing loan, personal loan, default history

Campaign Details: Contact method, campaign duration, number of contacts

Economic Indicators: Employment rate, Euribor rate, consumer price index

Target Variable:

y → Whether the client subscribed to a term deposit (yes / no)

🔍 Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

Age distribution of customers

Job-wise customer distribution

Average employment index vs deposit subscription

Effectiveness of contact methods

Campaign contact frequency comparison

Correlation heatmap of numerical features

These visualizations help identify important patterns and influential features affecting subscription decisions.

⚙️ Data Preprocessing

Steps applied before modeling:

Converted categorical features using Label Encoding

Selected numerical features for correlation analysis

Standardized features using StandardScaler

Split dataset into training (75%) and testing (25%)

🤖 Machine Learning Model

Algorithm Used: Logistic Regression

Reason: Simple, interpretable, and effective for binary classification

Libraries:

scikit-learn

pandas

matplotlib

seaborn

📈 Model Performance

The Logistic Regression model achieved:

Accuracy: 91.13%

Strong precision for non-subscribers

Moderate recall for subscribers (class imbalance observed)

Classification Report Summary:

The model performs well overall

Campaign duration and contact frequency strongly influence predictions

Economic indicators are significant predictors

🧩 Key Insights

Certain age groups and job categories are more likely to subscribe

Longer campaign duration increases subscription probability

Cellular contact performs better than telephone

Economic variables like euribor3m and employment rate are strong predictors

🛠️ Technologies Used

Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

Jupyter Notebook

🚀 How to Run the Project

Clone the repository

git clone <repository-url>


Install dependencies

pip install pandas matplotlib seaborn scikit-learn


Run the notebook in Jupyter Notebook / Anaconda

Ensure data.csv is in the same directory

📌 Conclusion

This project demonstrates how data analysis and machine learning can be used to improve decision-making in banking marketing campaigns. Logistic Regression provides strong baseline performance and valuable interpretability for business insights.
