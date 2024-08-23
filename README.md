# MLFlow-for-MLOps

To install the mlflow conda environment in the project folder, inside your terminal navigate to the project folder and then run the conda command:

```cmd
conda env create -f mlflow_env.yaml
```

This command will install environment with name mlflow and then you can activate the environment by using command:

```cmd
conda activate mlflow
```

## Common Gotchas while running MLFlow in Jupyter environment:

1. Not running the logging code in the same cell in the notebook.
2. Partial logging or logging parameters before the model training.
3. Not running the server before hand and running the logging code inside your notebook.
4. Writing the parameter names by hand in a complex sklearn pipeline or column transformer object with multiple sub-parameters.
