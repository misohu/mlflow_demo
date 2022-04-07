# MlFlow demo by Michal Hucko 

This repo contains demonstration on how to use mlflow in local setup. 

## Prerequisities

```{bash}
pip install mlflow==1.24.0
pip install jupyterlab
pip install scikit-learn
mlflow server --backend-store-uri sqlite:///mlflow.db --default-artifact-root ./artifacts --host 0.0.0.0
```

Server will be running at localhost:5000