# Heart Disease Report by Machine Learning (ML Project 1)

![Heart Health](https://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Heart_icon.svg/1024px-Heart_icon.svg.png)

This project leverages machine learning techniques to predict the presence of heart disease in patients based on their medical attributes and test results. It aims to demonstrate the power of machine learning in the healthcare domain, specifically in predictive diagnostics.

---

## Project Structure

```
📂 Heart_Disease_Report_ML
├── data
│   ├── heart.csv
├── notebooks
│   ├── data_analysis.ipynb
│   ├── model_building.ipynb
│   ├── model_evaluation.ipynb
├── scripts
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── results
│   ├── model_metrics.txt
│   ├── confusion_matrix.png
│   ├── ROC_curve.png
├── README.md
└── requirements.txt
```

---

## Goals

1. **Data Exploration and Visualization:** Analyze the dataset for trends, missing values, and outliers.
2. **Feature Engineering:** Create and preprocess features to enhance model accuracy.
3. **Model Development:** Build machine learning models such as Logistic Regression, Random Forest, and Support Vector Machines (SVM).
4. **Model Evaluation:** Evaluate models using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

---

## Dataset

The dataset used in this project is [Heart Disease UCI](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).  
Key attributes in the dataset:
- Age
- Sex
- Chest Pain Type (4 values)
- Resting Blood Pressure
- Serum Cholesterol (mg/dl)
- Fasting Blood Sugar > 120 mg/dl
- Resting Electrocardiographic Results
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- Oldpeak (ST depression induced by exercise)
- Slope of the peak exercise ST segment
- Number of major vessels (0-3) colored by fluoroscopy
- Thalassemia (3 values)

---

## Implementation Steps

1. **Data Preprocessing:**
   - Handle missing data.
   - Normalize and scale numerical attributes.
   - Encode categorical variables.

2. **Exploratory Data Analysis (EDA):**
   - Visualize distributions and correlations.
   - Identify patterns and trends.

3. **Model Building:**
   - Train various machine learning models.
   - Optimize hyperparameters using GridSearchCV.

4. **Evaluation:**
   - Compare model performance using metrics.
   - Select the best-performing model.

5. **Reporting:**
   - Visualize results using confusion matrices, ROC curves, and other plots.

---

## Key Results

- **Best Model:** Random Forest Classifier  
- **Accuracy:** IN PROGRESS 
- **ROC-AUC Score:** IN PROGRESS  

Confusion Matrix:  
![Confusion Matrix](https://via.placeholder.com/500x300?text=Confusion+Matrix)

ROC Curve:  
![ROC Curve](https://via.placeholder.com/500x300?text=ROC+Curve)


---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Heart_Disease_Report_ML.git
   cd Heart_Disease_Report_ML
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the preprocessing script:
   ```bash
   python scripts/data_preprocessing.py
   ```

4. Train the model:
   ```bash
   python scripts/model_training.py
   ```

5. Evaluate the model:
   ```bash
   python scripts/evaluation.py
   ```

---

## Tools & Libraries

- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-Learn

---

## Contributing

Contributions are welcome! Fork this repository and create a pull request with your changes.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Happy Coding! ❤️
