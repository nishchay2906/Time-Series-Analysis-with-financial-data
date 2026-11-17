# Financial time-series modeling

Coursework that builds lagged features and compares regression models, including tree ensembles and an LSTM, to estimate a missing closing price using a set of financial series.

## Run the notebook

1. Place the original assignment workbook, `MMA823_AssignmentData_topost.xlsx`, in the repository root. The workbook is absent from this repository.
2. Open [the notebook](Individual%20assignment%20823%20-%20Nishchay%20Vermani.ipynb) in JupyterLab from the repository root.
3. The notebook uses NumPy, pandas, openpyxl, Matplotlib, seaborn, pandas-datareader, scikit-learn, XGBoost, LightGBM, statsmodels, TensorFlow and Keras. The LSTM section uses the legacy `keras.wrappers.scikit_learn` API, which requires a compatible legacy environment.

## Evaluation

The saved notebook uses shuffled cross-validation and fits some preprocessing before splitting. A forecasting evaluation should use chronological splits and fit transformations within each training window.
