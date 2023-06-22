# Credit-Card-Fraud-Detection
### Problem Statement:
The objective of this project is to develop machine learning models for the detection of fraudulent credit card transactions. The dataset used in this project consists of customer-level data collected and analyzed by Worldline and the Machine Learning Group, containing a total of 284,807 transactions, of which 492 are fraudulent. Due to the highly imbalanced nature of the dataset, appropriate handling techniques will be applied prior to model building.

### Business Problem Overview:
Banks face the challenge of retaining high-profitable customers as their primary business goal. However, banking fraud poses a significant threat to this objective, leading to substantial financial losses and undermining trust and credibility for both banks and customers. It has been projected that banking frauds would reach $30 billion worldwide by 2020, emphasizing the need for proactive monitoring and fraud prevention mechanisms, particularly in the era of digital payment channels. Machine learning plays a crucial role in enabling financial institutions to implement efficient and timely fraud detection systems, reducing manual reviews, costly chargebacks, and denial of legitimate transactions.

### Understanding and Defining Fraud:
Credit card fraud encompasses any unauthorized act or behavior aimed at obtaining financial gain by dishonest means, without the account holder's proper authorization. Various methods of credit card fraud include skimming (duplication of magnetic strip information), manipulation/alteration of genuine cards, creation of counterfeit cards, theft/loss of credit cards, and fraudulent telemarketing.

### Data Dictionary:
The dataset used in this project can be downloaded from the provided link. It consists of credit card transactions made by European cardholders during a two-day period in September 2013. Among 284,807 transactions, 492 were identified as fraudulent. To maintain confidentiality, the dataset underwent Principal Component Analysis (PCA), resulting in features represented as V1 to V28, except for 'time' (elapsed time between first and subsequent transactions) and 'amount' (transaction amount). The 'class' feature denotes the transaction's label, taking the value 1 for fraud and 0 for non-fraud cases.

### Project Pipeline:
The project pipeline involves the following key steps:

- Data Understanding:

Load the dataset and gain an understanding of the available features.
Select relevant features for the final model.

- Exploratory Data Analytics (EDA):

Perform univariate and bivariate analyses of the data.
Consider feature transformations if necessary, while noting that PCA has already been applied.
Identify and mitigate any skewness in the data that may impact model building.

- Train/Test Split:

Divide the data into training and testing sets to assess model performance on unseen data.
Utilize k-fold cross-validation with an appropriate k value, ensuring representation of the minority class in test folds.

- Model Building/Hyperparameter Tuning:

Explore different machine learning models and fine-tune their hyperparameters.
Aim to achieve the desired level of performance on the dataset.
Consider employing various sampling techniques to improve model performance.

- Model Evaluation:

Evaluate the models using suitable evaluation metrics.
Given the imbalanced data, prioritize accurate identification of fraudulent transactions.
Select an appropriate evaluation metric aligned with this business goal.


By following this project pipeline, we aim to develop robust machine-learning models capable of effectively detecting fraudulent credit card transactions.
