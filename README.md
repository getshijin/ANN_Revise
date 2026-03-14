# ANN_Revise

A minimal project for experimenting with an Artificial Neural Network (ANN) workflow on the `Churn_Modelling.csv` dataset.

## What is in this repo
- `experiment.ipynb` — main notebook for data preprocessing and ANN experimentation.
- `Churn_Modelling.csv` — source dataset used by the notebook.
- `requirements.txt` / `Pipfile` — Python dependencies.

## Quick start
1. Create and activate a Python environment (Python 3.12 recommended).
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook experiment.ipynb
   ```

## Dependencies
Core libraries used:
- TensorFlow
- pandas
- NumPy
- scikit-learn
- tensorboard
- matplotlib
- streamlit

## Notes
- Keep `Churn_Modelling.csv` in the project root so notebook paths work without edits.
- This repository is currently centered on notebook-based experimentation.
