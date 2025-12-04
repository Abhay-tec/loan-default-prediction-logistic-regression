Credit Card Default Prediction – IBM SPSS Modeler

By: Abhay Dubey (3BCA – AI/ML), AKS University

📌 Objective

To build a predictive model that identifies whether a customer will default on their credit card payment next month using IBM SPSS Modeler.

🗂️ Dataset

Source: UCI "Default of Credit Card Clients"

Records: 30,000

Target: default.payment.next.month

Features: Limit balance, payment history, bill amounts, demographics, etc.

🛠️ SPSS Modeler Workflow

Loaded the dataset

Performed Data Audit

Assigned field roles (Input / Target)

Built a C5.0 Decision Tree Model

Evaluated using the Analysis Node

Checked accuracy, confusion matrix, and ROC curve

📊 Model Results

Model Type: C5.0 Decision Tree

Accuracy: ~81%

AUC: 0.728

Correct Predictions: 24,333

Incorrect Predictions: 5,667

Shows solid performance for default detection.

📂 Repository Includes

SPSS Modeler Stream File (.str)

Workflow screenshots

Evaluation results (Confusion matrix, AUC)

README documentation

✅ Conclusion

The project successfully builds a predictive model to classify customers likely to default on payments.
This model can help financial institutions improve credit scoring and risk management.
