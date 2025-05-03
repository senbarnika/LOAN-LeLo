_**Loan Approval & Eligibility Prediction Using Machine Learning**_

The  project leverages machine learning algorithms to automate and predict loan approval and eligibility based on various applicant features like income, credit history, marital status, etc. 
This project is designed to help financial institutions streamline the loan approval process, reduce manual work, and enhance decision-making accuracy.</br>

Loans are critical in today's economy, providing individuals with the capital they need to meet their personal, educational, or business goals. 
By implementing machine learning, banks can effectively predict the likelihood of an applicant being approved for a loan, increasing operational efficiency and customer satisfaction.</br>

![image](https://github.com/user-attachments/assets/52c50d61-c957-401b-bab4-067667efaef1)


**Libraries Used**

_Pandas_: For loading, handling, and preprocessing data in DataFrames.</br>
_Numpy_: For numerical operations on the dataset.</br>
_Matplotlib_: For data visualization, such as bar plots, pie charts, and heatmaps.</br>
_Seaborn_: For statistical data visualization, such as correlation heatmaps and pair plots.</br>
_Scikit-learn_: For machine learning models, preprocessing, and evaluation.</br>
_Imbalanced-learn_: For handling imbalanced datasets (RandomOverSampler).</br>
_LabelEncoder_: For converting categorical data to numerical data.</br>

**Data Preprocessing and Exploration**

i) _Handle Missing Values_: Fill any missing values in the dataset with mean values to prevent errors during model training.</br>
ii) _Categorical Variables Encoding_: Convert categorical data (e.g., Gender, Marital Status) into numerical labels using LabelEncoder.</br>
iii) _Data Correlation_: Visualize correlations between features to identify potential relationships using a heatmap.</br>

**Visualizations**

_Bar Plots_: For visualizing the distribution of categorical variables.</br>
_Heatmap_: To see the correlation between features and their relationship with the target variable (Loan_Status).</br>
_Catplot_: For visualizing relationships between categorical variables (e.g., Gender vs. Marital Status).</br>
_Pie Chart_: To visualize the distribution of loan approvals in the dataset.</br>
