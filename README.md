# Heart Disease Prediction — Final Year Project

## Setup
```bash
pip install -r requirements.txt
```

## Step 1 — Get the dataset
Download heart.csv from:
https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

Save it as:  data/heart.csv

## Step 2 — Run notebooks in order
```
jupyter notebook
```
Open and run each notebook top to bottom:
- notebooks/01_eda.ipynb
- notebooks/02_preprocessing.ipynb
- notebooks/03_model_training.ipynb
- notebooks/04_evaluation.ipynb
- notebooks/05_shap_explainability.ipynb

## Step 3 — Launch the web app
```bash
cd app
streamlit run app.py
```

## Project Structure
```
heart-disease-prediction/
├── data/               <- Put heart.csv here
├── notebooks/          <- Run these in order (01 to 05)
├── src/                <- Python helper modules
├── models/             <- Saved models (auto-created after training)
├── app/                <- Streamlit web app
├── report/             <- Charts saved here automatically
├── requirements.txt
└── README.md
```
