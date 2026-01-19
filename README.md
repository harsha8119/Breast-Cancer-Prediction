Project Overview:
This project focuses on building a **machine learning classification model** to predict whether a breast tumor is **benign or malignant** based on medical diagnostic features. The objective is to apply the end-to-end **machine learning workflow** — from data understanding and preprocessing to model training, evaluation, and prediction — using Python.

Problem Statement:
Early detection of breast cancer plays a critical role in improving patient survival rates. By analyzing numerical features extracted from breast mass images, this project aims to classify tumors accurately and support data-driven medical analysis.

Technologies & Libraries Used:
- **Python**
- **NumPy & Pandas** – Data manipulation and analysis
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models and evaluation

Dataset Description:
The dataset contains multiple numeric features that describe characteristics of cell nuclei, such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Concavity

The target variable represents:
- **Benign (non-cancerous)**
- **Malignant (cancerous)**

Data Loading & Exploration:
- Loaded the dataset and inspected its structure.
- Checked for missing values and data consistency.
- Analyzed feature distributions and class balance.

Data Preprocessing:
- Converted categorical labels into numerical format.
- Selected relevant features for model training.
- Split the dataset into **training and testing sets** to evaluate model performance objectively.
- Applied feature scaling where required to improve model accuracy.

Model Building:
- Trained a machine learning **classification algorithm** to learn patterns from the data.
- The model learns relationships between diagnostic features and tumor classification.

Model Evaluation:
- Evaluated the model using metrics such as:
  - Accuracy score
  - Confusion matrix
  - Classification report
- Verified how well the model distinguishes between benign and malignant cases.

Prediction:
- Used the trained model to predict breast cancer outcomes on unseen test data.
- Interpreted prediction results to validate model reliability.
