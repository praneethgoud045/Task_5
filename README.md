# Task_5
Consumer-Complaints Prediction
## Description

This repository contains Task 5 of the ML project(Consumer_complaints). It includes data processing, model training, and evaluation steps implemented in a Jupyter Notebook.

## Author

**L E Sree Sai Praneeth Goud**

## Setup

1. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Open the Jupyter Notebook:
   ```sh
   jupyter notebook notebooks/Task5.ipynb
   ```
3. Run the notebook step by step to execute the ML workflow.

## Dataset

- The dataset used in this task is located in the `link` provided below as dataset is very large.
- If the dataset is too large, please download it from [https://www.consumerfinance.gov/data-research/consumer-complaints/].

## Project Structure

```
/ML-Project
│── /data              # Dataset files (if applicable)
│── /notebooks         # Jupyter Notebook files
│── /results           # Screenshots of input/output
│── README.md          # Documentation
```

## Screenshots:
![algorithms_accuracys](https://github.com/user-attachments/assets/c50b0ce7-9342-4175-a2c7-a19d104869eb)
![accuracy_randomforet](https://github.com/user-attachments/assets/876bf0d0-158b-4d2f-b377-6d362a3dbfa8)

![wheel_graph](https://github.com/user-attachments/assets/204fae81-cf1f-47f4-931a-c873b5468c10)

![category_graph](https://github.com/user-attachments/assets/47f32a7c-80cf-4e44-91af-297163011a3a)
![confusion_matrix](https://github.com/user-attachments/assets/0c40beaf-a1bb-4f57-bbb7-7876ed80ba7e)





### Sample Dataset Preview

![image](https://github.com/user-attachments/assets/4bb10be3-0d71-4b9c-850b-45a75b35c91e)


Cleaned_dataset:


![cleaned_dataset_properties](https://github.com/user-attachments/assets/cdc62e83-de91-4aa6-bb9e-baada8827eb6)



### Model Training Output:

![image](https://github.com/user-attachments/assets/81244fbf-3237-4afc-8b20-c4665950fe92)




Trained multiple models, including:
1)Naive Bayes
2)Logistic Regression (with class_weight="balanced")
3)Random Forest (with class_weight="balanced")



### Final Model Evaluation

![predictions_sc](https://github.com/user-attachments/assets/7e12688b-34c4-4e89-898d-2f3c1defa9fa)



## Results

The notebook generates the following outputs:

- Model training results
- Performance metrics
- Graphs and charts for evaluation

- 🚀 Summary of Your Evaluation
✔️ Model Training Results → Naive Bayes, Logistic Regression, and Random Forest
✔️ Performance Metrics → Accuracy, Classification Report, Confusion Matrix
✔️ Evaluation Graphs & Charts → Confusion Matrix, Class Distribution, Feature Importance
