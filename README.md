# Classification-Problem-DT-RF-and-ANN
An Insurance firm providing tour insurance is facing higher claim frequency. The management decides to collect data from the past few years. You are assigned the task to make a model which predicts the claim status and provide recommendations to management. Use CART, RF & ANN and compare the models' performances in train and test sets.

Attribute Information:
----------------------

1. Target: Claim Status (Claimed)
2. Code of tour firm (Agency_Code)
3. Type of tour insurance firms (Type)
4. Distribution channel of tour insurance agencies (Channel)
5. Name of the tour insurance products (Product)
6. Duration of the tour (Duration)
7. Destination of the tour (Destination)
8. Amount of sales of tour insurance policies (Sales)
9. The commission received for tour insurance firm (Commission)
10. Age of insured (Age)

Steps:
------
1 Data Ingestion: Read the dataset. Do the descriptive statistics and do null value condition check, write an inference on it.
2 Data Split: Split the data into test and train, build classification model CART, Random Forest, Artificial Neural Network
3 Performance Metrics: Check the performance of Predictions on Train and Test sets using Accuracy, Confusion Matrix, Plot ROC curve and get ROC_AUC score for each model
4 Final Model: Compare all the model and write an inference which model is best/optimized.
5 Inference: Basis on these predictions, what are the business insights and recommendations
