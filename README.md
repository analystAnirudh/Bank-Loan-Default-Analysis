📊 Bank Loan Case Study

🏦 Project Overview
In this project, we analyze loan application data to identify patterns that influence loan default risk. The goal is to help financial institutions make informed lending decisions, reducing financial risk while ensuring deserving applicants get approved.
===============================================================================================================================================================================================================================================================================
📌 Key Business Challenges
Loan Approval Dilemma:

Approving high-risk applicants leads to financial loss.

Rejecting low-risk applicants results in lost business.

Understanding Default Patterns:

Identify attributes influencing loan repayment behavior.

Recognize high-risk customers early.
===============================================================================================================================================================================================================================================================================

🎯 Objectives
✅ Detect patterns in customer demographics and loan attributes.
✅ Identify factors leading to loan default.
✅ Improve loan approval decision-making.
===============================================================================================================================================================================================================================================================================

📂 Dataset Details
The dataset contains loan application records, covering:

Customer Information (e.g., age, income, employment type).

Loan Details (e.g., amount, term, interest rate).

Loan Status (e.g., approved, rejected, defaulted).
===============================================================================================================================================================================================================================================================================

🔍 Loan Status Categories

Status	Description
✅ Approved	Loan approved by the company.
❌ Refused	Loan rejected due to risk factors.
🔄 Cancelled	Customer withdrew during approval.
🛑 Unused Offer	Approved but not utilized.
📊 Data Analytics Tasks & Approach
🔎 A. Handling Missing Data
==============================================================================================================================================================================================================================================================================
Task: Identify and address missing data in loan applications.
📌 Methods:
Use COUNT, ISBLANK, and IF functions in Excel.

Impute missing values with AVERAGE or MEDIAN.

Graph: 📊 Bar Chart of missing values per column.
===============================================================================================================================================================================================================================================================================

📉 B. Identifying Outliers
Task: Detect and handle outliers affecting analysis.
📌 Methods:
===============================================================================================================================================================================================================================================================================
Calculate Interquartile Range (IQR) using QUARTILE.

Apply Conditional Formatting to highlight extreme values.

Graph: 📊 Box Plot / Scatter Plot to visualize outliers.
===============================================================================================================================================================================================================================================================================
⚖️ C. Data Imbalance Analysis
Task: Evaluate distribution of loan approval vs. default cases.
📌 Methods:

Use COUNTIF and SUM for class proportions.

Graph: 📊 Pie Chart / Bar Chart for target variable distribution.
===============================================================================================================================================================================================================================================================================
📈 D. Univariate, Segmented & Bivariate Analysis
Task: Explore relationships between variables.
📌 Methods:

COUNT, AVERAGE, MEDIAN for univariate analysis.

Pivot tables & sorting for segmented analysis.

Scatter plots & heatmaps for bivariate analysis.

Graphs: 📊 Histograms, Bar Charts, Stacked Bar Charts, Scatter Plots.
===============================================================================================================================================================================================================================================================================
🔗 E. Correlation Analysis
Task: Identify key factors linked to loan default.
📌 Methods:

Calculate correlations with CORREL function.

Rank key risk indicators.

Graph: 📊 Correlation Matrix / Heatmap for visualization.
===============================================================================================================================================================================================================================================================================
🛠️ Technology & Tools Used
🔹 Excel (Data Cleaning, EDA, Visualization)

