# deep Classifier Project 

## workflow

Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config.
Update the components
Update the pipeline
Test run pipeline stage
run tox for testing your package
Update the dvc.yaml
run "dvc repro" for running all the stages in pipeline

![img](https://raw.githubusercontent.com/c17hawke/FSDS_NOV_deepCNNClassifier/main/docs/images/Data%20Ingestion%402x%20(1).png)

STEP 1: Set the env variable | Get it from dagshub -> remote tab -> mlflow tab


MLFLOW_TRACKING_URI=https://dagshub.com/manotti22/deepCNNClassifier.mlflow 
MLFLOW_TRACKING_USERNAME=manotti22 
MLFLOW_TRACKING_PASSWORD=your_token  


STEP 2: install mlflow

STEP 3: Set remote URI

STEP 4: Use context manager of mlflow to start run and then log metrics, params and model

## Sample data for testing-
https://raw.githubusercontent.com/c17hawke/raw_data/main/sample_data.zip