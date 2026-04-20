# Skin Disease Prediction Using Machine Learning

## Project Overview

Skin diseases belonging to the erythemato-squamous group often share similar clinical symptoms such as redness, scaling, and itching, making accurate diagnosis challenging. Traditionally, dermatologists rely on both clinical observations and histopathological examinations to differentiate between these diseases.

This project applies **machine learning techniques** to analyze clinical and microscopic attributes in order to predict the type of skin disease. The developed model assists in identifying patterns in the data and provides a predictive system that can support dermatologists in early diagnosis.

---

## Dataset Information

The dataset contains **clinical and histopathological features** used to classify six types of erythemato-squamous diseases.

### Diseases Included

1. Psoriasis  
2. Seborrheic Dermatitis  
3. Lichen Planus  
4. Pityriasis Rosea  
5. Chronic Dermatitis  
6. Pityriasis Rubra Pilaris  

### Dataset Characteristics

- Total Attributes: **34**
- Clinical Features: **12**
- Histopathological Features: **22**
- Target Variable: **Disease Class**

Most attributes are measured on a **scale from 0 to 3**, where:

- **0** → Feature not present  
- **1–2** → Intermediate levels  
- **3** → Maximum presence of the feature

The **Age** attribute is a continuous variable representing the patient's age.

---

## Project Objectives

The main objectives of this project are:

- Perform **Exploratory Data Analysis (EDA)** to understand dataset patterns.
- Apply **data preprocessing techniques** to clean and prepare the dataset.
- Train multiple **machine learning classification models**.
- Evaluate model performance using standard metrics.
- Identify the **best performing model** for skin disease prediction.
- Provide insights that can support **medical decision making**.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

The project follows a structured machine learning workflow:

### 1. Data Collection

The dermatology dataset was obtained from a public repository and contains clinical and histopathological attributes used for disease classification.

### 2. Data Preprocessing

The dataset required preprocessing steps including:

- Handling missing values in the **Age** column
- Converting data types
- Preparing features for machine learning models

### 3. Exploratory Data Analysis

EDA was performed to understand:

- Distribution of disease classes
- Age distribution among patients
- Relationships between clinical features
- Feature correlations

Several visualizations were created to gain insights into the dataset.

### 4. Model Development

Multiple classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine

### 5. Model Evaluation

Models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Model Performance Comparison

| Model | Accuracy |
|------|------|
| Logistic Regression | ~95% |
| Decision Tree | ~96% |
| Support Vector Machine | ~97% |
| Random Forest | **~98–99%** |

Among all tested models, **Random Forest achieved the highest accuracy and best overall performance.**

---

## Why Random Forest Was Selected

Random Forest was selected as the final model because:

- It uses **ensemble learning**, combining multiple decision trees.
- It reduces **overfitting** compared to single decision trees.
- It performs well with **high-dimensional datasets**.
- It provides **high predictive accuracy**.

These advantages make Random Forest highly suitable for complex classification tasks like skin disease prediction.

---

## Key Insights

Analysis of the dataset revealed that several clinical and microscopic features strongly influence disease classification. Important indicators include:

- Erythema
- Scaling
- Acanthosis
- Hyperkeratosis
- Parakeratosis

Understanding these features helps improve diagnostic accuracy.

---

## Suggestions for Doctors

Based on the analysis, the following recommendations can support early diagnosis:

- Carefully evaluate **clinical symptoms** such as redness, scaling, and itching.
- Consider **histopathological indicators** when symptoms overlap between diseases.
- Use **machine learning assisted diagnostic systems** as decision support tools.
- Early detection can significantly improve treatment outcomes.

---

## Conclusion

This project demonstrates the effectiveness of machine learning techniques in predicting erythemato-squamous skin diseases using clinical and histopathological attributes.

Among the evaluated models, **Random Forest achieved the best performance**, providing high classification accuracy and reliable predictions.

The results highlight the potential of machine learning as a **support tool for dermatologists**, helping improve diagnostic efficiency and enabling earlier detection of skin diseases.

---

## Future Scope

Future improvements to this project may include:

- Expanding the dataset with more patient records
- Implementing deep learning techniques
- Deploying the model as a **web-based diagnostic application**
- Integrating the system with hospital information systems

---

## Author
VIKASINI D

This project was developed as part of a **Machine Learning Capstone Project** focused on applying data science techniques to healthcare data alongside my internship with Rubixe
