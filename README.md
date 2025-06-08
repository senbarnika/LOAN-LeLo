_**Loan Approval & Eligibility Prediction Using Machine Learning**_

The  project leverages machine learning algorithms to automate and predict loan approval and eligibility based on various applicant features like income, credit history, marital status, etc. 
This project is designed to help financial institutions streamline the loan approval process, reduce manual work, and enhance decision-making accuracy.</br>

Loans are critical in today's economy, providing individuals with the capital they need to meet their personal, educational, or business goals. 
By implementing machine learning, banks can effectively predict the likelihood of an applicant being approved for a loan, increasing operational efficiency and customer satisfaction.</br>

![image](https://github.com/user-attachments/assets/52c50d61-c957-401b-bab4-067667efaef1)

**Project Structure**


![image](https://github.com/user-attachments/assets/dfd19211-ecae-4ea6-b197-da2f7c954380)

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

**Result Table (Post-Implementation Idea)**
| Model                    | Training Accuracy | Testing Accuracy |               
| ------------------------ | ----------------- | ---------------- | 
| Random Forest Classifier | 98.04%            | 82.50%           |              
| K-Nearest Neighbors      | 78.49%            | 63.75%           |               
| Support Vector Machine   | 68.71%            | 69.17%           |               
| Logistic Regression      | 80.45%            | 80.83%           |

[1]: https://github.com/sonikirtan110/Credit-Card-Fraud-Detection?utm_source=chatgpt.com "sonikirtan110/Credit-Card-Fraud-Detection: \"A project to ... - GitHub"

_Note: The Random Forest Classifier achieved the highest accuracy on the testing dataset. Further improvements can be explored using ensemble techniques like Bagging and Boosting._

**Conclusion — **Why LOAN LeLo?****

I’ve named this project (Loan Approval & Eligibility Prediction)-> “LOAN LeLo” to reflect its user-friendly and real-world applicability — a smart, data-driven engine that simplifies credit decisions. Unlike typical loan approval or prediction systems, LOAN LeLo is built not just to classify but to intelligently evaluate a user’s credit profile using both traditional Machine Learning algorithms and ensemble techniques like Bagging and Boosting, enhancing robustness and accuracy.

How LOAN LeLo Works? :</br>

Data Ingestion: Cleans and preprocesses loan applicant data.</br>
Model Pipeline: Applies Logistic Regression, Decision Trees, Random Forests, and ensemble methods (like Bagging & Boosting) for comparative insights.</br>
Prediction Engine: Accurately predicts both loan eligibility and approval probability.</br>
Visualization: Graphs and heatmaps help explain model outputs, making the system transparent and trustworthy.</br>

 What Sets LOAN LeLo Apart? :</br>
 
1) Dual-Purpose: Handles both eligibility prediction and approval classification — rarely offered together.</br>

2) Model Comparison Built-In: Users can see how different models perform and why certain predictions are made.</br>

3) Scalability-Ready: Modular architecture supports easy integration with dashboards or APIs for real-time deployment.</br>

4) Explainability: Clear plots, confusion matrices, and metrics help stakeholders understand decisions.</br>

5) Extendability: You can add features like customer profiling, dynamic thresholding, or even integrate with banking APIs.</br>
