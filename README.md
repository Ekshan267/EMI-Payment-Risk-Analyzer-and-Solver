# EMI Payment Risk Analyzer and Solver

This repository contains the code and resources for a machine learning project that predicts the probability of a customer not paying EMI in the next month. The main code is provided in the Jupyter Notebook named `MetaData_CanaraDACOE.ipynb`. This notebook is trained on the `Training Data File.csv` and validated on the `Validation Data File.csv`.

## Project Overview

In this project, we aim to develop a prediction model for identifying customers who are at risk of not paying their EMI in the next month. This model is essential for the banking and financial sector to manage risks and portfolio effectively. To further enhance the project, we have integrated an automated reminder system using GenAI with our prediction model. The goal is to proactively reach out to customers who are potentially at risk of not making their EMI payments.

## Evaluation Metrics

We will evaluate the performance of our model using the following metrics:

- Classification Report: This report provides detailed information about precision, recall, and F1-score for each class.
- ROC AUC Score: This score measures the model's ability to discriminate between positive and negative classes.

In the BFSI sector, accuracy is crucial, and we cannot compromise on it. The model's performance will be assessed based on these metrics.

## Key Outcomes

Using a Random Forest Classifier with specific hyperparameters, we achieved the following results:

- Accuracy: 0.98, indicating that the model correctly classifies approximately 98% of the samples.
- Precision: 0.98 for the negative class (Class 0) and 0.95 for the positive class (Class 1).
- Recall: 0.99 for Class 0 and 0.88 for Class 1.
- F1-Score: Excellent for both Class 0 (0.99) and Class 1 (0.92).
- Macro Average F1-Score: 0.95, and Weighted Average F1-Score: 0.98.
- AUC Score: 0.975, indicating the model's strong discrimination ability between classes.

The Random Forest Classifier, configured with the specified hyperparameters, represents a balanced model with strong performance in correctly identifying both negative and positive classes.

## Integration and Tools Used

- Prediction table and customer info table are joined to focus on non-payers.
- We have used the LLM API for generating reminder content.
- The MIME library is utilized for automated email sending.
- The project can be scheduled for automation using Alteryx or other relevant tools to operate at an industrial level.

## Demo Video and Presentation

You can find a demo video showcasing the project's functionality [here]([#insert_demo_video_link](https://drive.google.com/file/d/1kur5EPmB5tilb4H6BdsZ2sZTK-8Roy03/view?usp=sharing)).

A presentation summarizing the project can be accessed [here]([#insert_presentation_link](https://docs.google.com/presentation/d/1e52ZE5xzNgqiKXe1dARr4F6Jx_Q4kUhX/edit?usp=sharing&ouid=118043978360514977350&rtpof=true&sd=true)).

Feel free to explore the Jupyter Notebook for the code and details of the project. If you have any questions or need further information, please reach out to the project contributors.

Thank you for your interest in our machine learning project!
