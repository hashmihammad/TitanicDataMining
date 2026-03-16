# Titanic Data Mining Project

## Overview
This project demonstrates **data mining and machine learning** using the famous **Titanic dataset**. The goal is to predict passenger survival using **Logistic Regression** after performing a complete data preprocessing and feature engineering process.

This repository contains the full workflow:  
- Data cleaning and handling missing values  
- Feature selection and transformation  
- Model training with Logistic Regression  
- Evaluation using accuracy, confusion matrix, and classification report  

This is a hands-on practice for learning the basics of **machine learning** and **data mining**.

---

## Files

| Filename        | Description |
|-----------------|-------------|
| `DM_Lab1.ipynb` | Jupyter notebook with complete code and explanations |
| `tested.csv`    | Dataset used for training and testing the model |

---

## Steps Performed

1. **Data Preprocessing**  
   - Checked for missing values  
   - Handled null values and transformed categorical features  

2. **Feature Selection**  
   - Selected relevant features for predicting survival  

3. **Modeling**  
   - Applied **Logistic Regression**  
   - Split the dataset into training and testing sets  

4. **Evaluation**  
   - Calculated **accuracy**  
   - Generated **confusion matrix**  
   - Produced **classification report** with precision, recall, and F1-score  

Example evaluation results:

```

Accuracy: 1.0
Confusion Matrix:
[[50  0]
[ 0 34]]
Classification Report:
precision    recall  f1-score   support

```
       0       1.00      1.00      1.00        50
       1       1.00      1.00      1.00        34

accuracy                           1.00        84
```

macro avg       1.00      1.00      1.00        84
weighted avg       1.00      1.00      1.00        84

````

---

## Technologies Used

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Scikit-learn  

---

## How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/TitanicDataMining
````

2. Open `DM_Lab1.ipynb` in **Jupyter Notebook**
3. Run all cells to see the full data mining workflow and model evaluation

---

## Learning Outcomes

* Hands-on experience with **data cleaning** and **preprocessing**
* Feature selection and handling categorical variables
* Training and evaluating a **Logistic Regression** model
* Understanding model performance metrics

---

## License

This project is **open source** and available under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, reach out via GitHub: [hashmihammad](https://github.com/hashmihammad)
Do you want me to do that next?
