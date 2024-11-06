**Credit Card Fraud Detection System**

This Credit Card Fraud Detection System project aims to identify and analyze fraudulent credit card transactions. The project involves data preprocessing, visualization, and exploratory analysis of transaction times and amounts to understand the distribution of legitimate versus fraudulent transactions. Given the dataset's imbalance, an under-sampling technique is applied to balance the data. The cleaned and scaled dataset is then split into training and testing subsets, where a Logistic Regression model is trained to classify transactions. The model's accuracy and performance are evaluated through precision, recall, and F1 scores to assess its ability to detect fraud effectively.

**Project Structure** 

Credit_Card_Fraud_Detection_System.py: file with all code for reading, analyzing, processing, training data and model evaluation
Sample_Data: Folder where you should place the sample data file creditcard.csv. Before running the program, please download the data from from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download
README.md: Project documentation

**Data Analysis**

1. **Distribution of Transaction Time and Amount (Original Data)**
   
   ![Original Data Distribution](Images/original_data_distribution.jpg)

2. **Legit vs Fraudulent Transactions Analysis**
   
   ![Legit and Fraudulent Transactions Analysis](Images/legit_fraudulent_transactions_analyze.jpg)

3. **Overview of Original DataFrame**
   
   ![Overview of Original DataFrame](Images/overview_original_dataframe.jpg)

4. **Mean Comparison by Class in Original Data**
   
   ![Mean Comparison - Original Data](Images/original_data_compare_by_mean.jpg)

**Data Processing**

5. **Mean Comparison by Class in New Dataset (After Under-Sampling)**

   ![Mean Comparison - New Dataset](Images/new_dataset_compare_by_mean.jpg)

6.**Distribution of Transaction Time and Amount (New Dataset)**

   ![New Data Distribution](Images/new_dataset_distribution.jpg)

**Performance Evaluation**

7. **Classification Report for Model Evaluation**

   ![Classification Report](Images/classification_report.jpg)
