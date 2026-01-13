# cancer-cell-detection-ml
Machine Learning project for cancer cell classification using ML models
## Project Report
The complete project implementation and results are available in:
- `cancer_cell_detection.pdf`
 ##Notebook
ML_cancer_cell_detection.ipynb

##Project Overview
Cancer cell detection is an important application of machine learning in the healthcare domain.
This project uses a tabular medical dataset containing numerical features extracted from cell samples to classify tumors as benign or malignant.
The objective is to build and evaluate machine learning classification models that can assist in early cancer diagnosis using structured data.

##The project follows a standard end-to-end machine learning pipeline 
 Data loading and understanding
 Exploratory Data Analysis (EDA)
 Data preprocessing
 Feature scaling
 Model training
 Model evaluation
 Performance comparison

##Machine Learning Models Used
This is a classification problem, and the following models were implemented:
Logistic Regression
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Random Forest Classifier
(Each model was trained and evaluated using the same dataset split for fair comparison)

##Model Evaluation
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
(Recall was given special importance because minimizing false negatives is critical in cancer detection)

##Results & Observations:
Tree-based and margin-based models performed better than distance-based models
Random Forest and SVM achieved strong accuracy and recall
The final selected model generalizes well on unseen test data

##Tech Stack
Programming Language: Python
Libraries Used:
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Development Environment: Jupyter Notebook

## How to Run the Project
git clone (https://github.com/Gitbrewhub/cancer-cell-detection-ml.git)
cd cancer-cell-detection-ml
pip install -r requirements.txt
Cancer_Cell_Detection.ipynb

#structure
cancer-cell-detection/
│
├── data/
│   └── cancer_data.csv
│
├── notebooks/
│   └── Cancer_Cell_Detection.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── results/
│   └── confusion_matrix.png
│
├── requirements.txt
└── README.md


## Limitations
- The dataset size is limited, which may affect model generalization on real-world data.
- The model relies only on numerical features and does not incorporate clinical images or genetic data.
- Hyperparameter tuning was kept minimal to maintain simplicity and learning focus.
- This model is intended for academic and educational purposes and should not be used for medical diagnosis.


