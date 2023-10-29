
## 🩺📷 Kidney-Disease-Classification


![example](https://drive.google.com/uc?export=view&id=1WulaI1M69m3-awmRvsYUa5YRLrmVNAYZ)

![result](https://drive.google.com/uc?export=view&id=1sHgDUU7JlJgAdUneBhxQG50ULu7_W-N8)

- This repository represents **"a deep learning-based Kidney Disease classifier"**.
- With the help of this project we can classify Kidney Disease.

## 📝 Description
- Utilized a pre-trained **VGG16** model for deep learning-based Kidney Disease classification.
- The end-to-end solution encapsulates a web app using **Docker**, **Flask**, and **HTML**.
- Deployed the solution on **AWS ECR** and **EC2** with tracking tools **DVC** and **mlflow**.

## ⏳ Dataset
- The original dataset is sourced from [Kaggle's Kidney Disease dataset](https://www.kaggle.com/datasets/akshayksingh/kidney-disease-dataset)
- Due to hardware limitations, a sampled version of the same dataset was utilized in the code.

## 🖥 Installation

### 🛠 Requirements
* tensorflow == 2.12.0
* pandas
* dvc
* mlflow == 2.2.2
* notebook
* numpy
* matplotlib
* seaborn
* python-box==6.0.2
* pyYAML
* tqdm
* ensure==1.0.2
* joblib
* types-PyYAML
* scipy
* Flask
* Flask-Cors
* gdown

## ⚙️ Setup
1. Clone the repository


```bash
https://github.com/wnsgh2254/Kidney-Disease-Classification-Deep-Learning-Project

```
2. Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```

3. install the requirements

```bash
pip install -r requirements.txt
```

## 🎯 Inference demo
1. Acticate conda environment
```bash
conda activate cnncls
```

2. Run app.py file on terminal(for MacOS)

```bash
$ python app.py
```

3. Copy and paste the last link to the browser.(in this case -> 192.168.1.113.8080)

![address](https://drive.google.com/uc?export=view&id=1UyZJQrC6ulAmCmjld-t-ZODJFvCByNyB)


## 📈 MLflow

* MLflow allows us to track model parameters, monitor results, and compare outcomes across different parameter settings

![mlflow1](https://drive.google.com/uc?export=view&id=1j9LPLuKMmoXidAvoSkCxQ01tTVt0sA5e)
![mlflow2](https://drive.google.com/uc?export=view&id=1pm2DKTQAjE5N-J0AvhXsWWAuzeLCINV7)

## ⛓ DVC

* DVC is a tool designed to handle large datasets and ML/DL models, making data science experiments reproducible.
* Integrates seamlessly with Git, allowing for versioning of datasets and ML models.
* Provides a visual pipeline representation, streamlining the experimentation process.

1. Acticate conda environment
```bash
conda activate cnncls
```

2. Run this to export as env variables

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/wnsgh2254/Kidney-Disease-Classification-Deep-Learning-Project.mlflow

export MLFLOW_TRACKING_USERNAME=wnsgh2254

export MLFLOW_TRACKING_PASSWORD=a24a1403dc1f5f4b6f985e06b428fb27e5f0100a

```

3. Run DVC cmd on Terminal.

```bash
dvc dag
```

4. Result

![Image](https://drive.google.com/uc?export=view&id=1yzDwA-vpKXfYEqs8srPN0bJmvdCfPi1z)





