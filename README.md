asyVisa Project – U.S. Work Visa Classification Model
📌 Problem Statement
Business communities across the United States are experiencing increasing demand for skilled labor. To remain competitive, companies often seek qualified talent beyond U.S. borders. While the Immigration and Nationality Act (INA) allows for hiring foreign workers on a temporary or permanent basis, it also mandates employer compliance to ensure no adverse impact on U.S. wages and working conditions.

The Office of Foreign Labor Certification (OFLC), which processes job certification applications, is increasingly overwhelmed by the volume of applications. In FY 2016 alone, the OFLC reviewed nearly 776,000 applications for approximately 1.7 million positions—a 9% increase from the previous year.

🎯 Project Objective
EasyVisa was contracted to develop a machine learning solution that automates the initial screening process for visa approval likelihood. As a data scientist, your role is to:

Analyze historical visa application data

Identify key features that influence visa approval

Build and evaluate a classification model

Provide recommendations to streamline OFLC’s decision-making process

📂 Project Structure
The notebook includes the following components:

Problem Definition

Data Overview and Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering

Model Selection and Evaluation

Business Recommendations

🧠 Methods Used
Classification Models (e.g., Logistic Regression, Random Forest, etc.)

SMOTE for handling class imbalance

Evaluation Metrics: Accuracy, Precision, Recall, F1-score

Confusion Matrix and ROC-AUC analysis

🗃️ Dataset
The dataset was sourced from the OFLC labor certification applications. Key variables include:

Case Status (e.g., Certified, Denied)

Job Title, Employer Name, Worksite Location

Prevailing Wage, Full-Time Position, etc.

📊 Key Insights
Wage and job location were significant predictors.

Full-time roles had a higher chance of approval.

Imbalanced classes required oversampling techniques (e.g., SMOTE) for effective model training.

🛠️ Tools & Libraries
Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn

Imbalanced-learn (for SMOTE)

🧩 Conclusion
The project highlights how data science can augment policy-driven institutions by automating manual processes and improving efficiency. The developed classification model can significantly reduce OFLC’s manual workload and accelerate visa processing timelines.

