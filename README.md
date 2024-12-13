# **Machine Learning for transaction analysis: Spending Prediction, Fraud Detection, Anomaly Identification, and Behavioral Clustering**  


## **Introduction**
This project utilizes transactional data from Nexus Bank to implement machine learning solutions that enhance customer experiences and optimize banking operations. By analyzing customer interactions and transaction histories, machine learning models provide actionable insights to address key challenges in the competitive financial sector.
- Use case 1: Financial planning optimization: Predict customers' total spending for the next month, assisting them in effective budgeting.
- Use case 2: Fraud detection enhancement: Detect fraudulent transactions to safeguard customer assets and reduce financial risks.
- Use case 3: Personalized marketing campaigns: Group customers with similar spending patterns for targeted marketing strategies.
- Use case 4: Proactive Customer Support: Identify and address abnormal spending behaviors to enhance customer satisfaction and loyalty.

## **Key objectives**
- Develop a Regression model to predict customers' total spending amount for the next month to aid in better financial budgeting.
- Develop a Classification model to identify fraudulent behaviors to enhance the bank's fraud detection capabilities.
- Implement Clustering techniques to segment customers based on spending behaviors to tailor marketing campaigns effectively.
- Utilize anomaly detection methods to proactively reach out to customers with abnormal spending patterns.
- Provide actionable recommendations to optimize financial budgeting, fraud detection, targeted marketing, and proactive customer support strategies.

## **Usage**

1. Open notebooks from the Drive folder [here](https://drive.google.com/drive/folders/1D4SKWBTjLtdHza9CZqfakqO8b1Siifq0?usp=sharing) in Google Colab.
2. Mount Google Drive by running the code block:
   
   `from google.colab import drive
   drive.mount('/content/drive')`
   
3. Run the code below to install requirements
   
   `! pip install -r https://github.com/phuonganh-38/transaction-analysis-ML/blob/main/requirements.txt`


## **Dataset**
- The dataset includes [transaction files](https://drive.google.com/drive/folders/1gnaiJyx1JHaf3_2PHcn6jV3xXym7lY1e?usp=sharing) containing customer properties and a file containing personal information of 1,000 [customers](customers.csv). These files are combined on two common columns (cc_num and acct_num).
- In total, there are 4,260,904 transactions from December 2018 to December 2022, including both legitimate and fraudulent transactions using credit cards of 1,000 customers.

These are the details of the dataset:

| Dataset          | Transaction file                 | Customer file     |
|-------------------|----------------------------------|-------------------|
| **Number of files** | 132                              | 1                 |
| **Name of files**   | `transactions_0.csv` to `transactions_131.csv` | `customers.csv`   |
| **Dimension**       | (4260904, 10)                  | (1000, 15)        |
| **Common columns**  | `cc_num`, `acct_num`           | `cc_num`, `acct_num` |


## **Features**


## **Models Used** 
- KNN
- Decision Tree
- Random Forest
- Isolation Forest

## **Version Used**
- pandas==2.1.1
- scikit-learn==1.2.2
- altair==4.2.2


## Authors
- **Phuong Anh Pham** - *Provided README*
See the list of [contributors](CONTRIBUTORS.md) who participated in this project.

## **Acknowledgements**
Special thanks to everyone who supported this project. 
