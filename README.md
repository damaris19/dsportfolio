# dsportfolio
A repo to showcase my data science and machine learning portfolio

## 🚀 Project Structure

- `data/raw/` — original datasets
- `data/processed/` — cleaned, transformed datasets
- `notebooks/` — Jupyter notebooks for EDA, modeling, evaluation
- `src/` — modular Python scripts for reproducible pipelines
- `models/` — saved model artifacts
- `app/` — Streamlit or FastAPI app for deployment

## 📊 Workflow

1. Run EDA in `01_eda.ipynb`
2. Build features in `02_feature_engineering.ipynb`
3. Train models in `03_modeling.ipynb`
4. Evaluate and compare models in `04_evaluation.ipynb`
5. Deploy using `app/streamlit_app.py`

project-template/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_evaluation.ipynb
│
├── src/
│   ├── data_prep.py
│   ├── features.py
│   ├── train_model.py
│   └── utils.py
│
├── models/
│
├── app/
│   └── streamlit_app.py
│
├── requirements.txt
├── .gitignore
└── README.md
