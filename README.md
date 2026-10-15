# Heart Disease EDA and Classification

This is a Python lab project using the Cleveland heart disease dataset. The notebook covers the 14 EDA tasks from the assignment and adds Logistic Regression and Random Forest as a classification exercise.

## Files

- `heart.csv` - dataset used in the notebook
- `heartdisease_eda.ipynb` - EDA, charts, findings and model comparison
- `eda_report.txt` - short report created by the last notebook cell
- `graphs/` - charts created when the notebook is run
- `requirements.txt` - libraries needed to run it

## Run

1. Extract the ZIP file.
2. Open a terminal in the extracted project folder.
3. Install the libraries with `python -m pip install -r requirements.txt`.
4. Start Jupyter with `jupyter notebook`, open `heartdisease_eda.ipynb`, and run all cells from top to bottom.

The original `num` column has values 0 to 4. In the ML part, 0 means no disease was recorded and values 1 to 4 are grouped as disease present. The models are for this class project only and should not be used for medical decisions.
