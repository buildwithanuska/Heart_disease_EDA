# Heart Disease EDA & Machine Learning

An exploratory data analysis and machine learning project using Python to analyze clinical data and identify patterns associated with heart disease.

## Objectives
- Explore clinical and demographic features.
- Handle missing values and duplicate records.
- Visualize patterns and relationships in the data.
- Train and evaluate machine learning classification models.

## Dataset
The project uses the **UCI Heart Disease dataset**, containing 303 records and 14 original columns.

The original `num` target (0–4) is converted into a binary target:
- `0` — No disease recorded
- `1` — Disease recorded (`num > 0`)

## Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Analysis & Visualizations
- Data inspection, cleaning, and summary statistics
- Univariate, bivariate, and multivariate analysis
- Correlation heatmap and outlier detection using IQR
- Age-group, chest-pain, and heart-rate analysis

Visualizations are saved in the `graphs/` directory.

##  Machine Learning
Two classification models are used:
- **Logistic Regression**
- **Random Forest Classifier**

Evaluation includes accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and stratified 5-fold cross-validation.

## Project Structure

```text
Heart-Disease-EDA-ML/
├── graphs/
├── heart.csv
├── heartdisease_eda.ipynb
├── eda_report.txt
├── requirements.txt
└── README.md
```

## Getting Started

```bash
git clone https://github.com/buildwithanuska/Heart_disease_EDA.git
cd Heart_disease_EDA
python -m venv .venv
```

Activate the environment on Windows and install dependencies:

```powershell
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
jupyter notebook
```

Open `heartdisease_eda.ipynb` and run the cells.

##  Limitations
- The dataset is relatively small and may not represent the wider population.
- Results show associations, not causation.
- This project is for educational purposes and is not a medical diagnostic tool.

## Author
**Anuska** · [GitHub](https://github.com/buildwithanuska)