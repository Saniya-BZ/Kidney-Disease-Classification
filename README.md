# Kidney-Disease-Classification


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Saniya-BZ/Kidney-Disease-Classification
```
### STEP 01- Create a conda environment after opening the repository

```bash
python -m venv venv
```

```bash
venv\Scripts\activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)


Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI= "URI"
export MLFLOW_TRACKING_USERNAME="USER NAME"
export MLFLOW_TRACKING_PASSWORD="PASSWORD"
python script.py

```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)

