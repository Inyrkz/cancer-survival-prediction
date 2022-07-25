# cancer-survival-prediction
Project on predicting the cancer survival rate of patients based on their gene expression data

The project notebook is `cancer_survival_rate.ipynb`. You can view the HTML file `cancer_survival_rate.html`.

To run the project, you'll need to install `Anaconda` in your system. Then open the `cancer_survival_rate.ipynb` with Jupyter Notebook or VSCode.
You'll also need to install `xgboost`. Run the code below in your terminal [Anaconda Prompt] to install `xgboost`.

```bash
conda install -c conda-forge xgboost
```

The project uses three models: `Random Forest`, `XGBoost`, and `Multi-Layer Perceptron` to predict the cancer survival rate of patients. The best performing model is the `Multi-Layer Perceptron`.
