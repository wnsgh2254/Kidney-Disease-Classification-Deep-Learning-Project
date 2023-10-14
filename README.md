# Kidney-Disease-Classification-Deep-Learning-Project

## WorkFlows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update teh entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipline
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/wnsgh2254/Kidney-Disease-Classification-Deep-Learning-Project
```


### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STETP 02- install the requirements
```bash
pip install -r requirements.txt
```


## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/wnsgh2254/Kidney-Disease-Classification-Deep-Learning-Project.mlflow \
MLFLOW_TRACKING_USERNAME=wnsgh2254 \
MLFLOW_TRACKING_PASSWORD=a24a1403dc1f5f4b6f985e06b428fb27e5f0100a \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/wnsgh2254/Kidney-Disease-Classification-Deep-Learning-Project.mlflow

export MLFLOW_TRACKING_USERNAME=wnsgh2254

export MLFLOW_TRACKING_PASSWORD=a24a1403dc1f5f4b6f985e06b428fb27e5f0100a

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