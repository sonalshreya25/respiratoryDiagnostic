# Respiratory Disease Diagnosis using Interpretable AI

This project uses machine learning models to classify respiratory conditions (Healthy, Infectious, Obstructive, Structural) based on respiratory sound data and related patient features. It integrates interpretable AI techniques to provide transparent predictions, helping clinicians understand which features contributed to each diagnosis.

## Features

? Multi-class classification (Healthy, Infectious, Obstructive, Structural)  
? ROC curve evaluation with AUC metrics  
? Interpretable AI outputs (feature importance, attention heatmaps)  
? Integrated with healthcare data pipelines (optional for hospital deployments)  

## Project Structure

- `models/` ? Trained models and saved weights  
- `src/` ? Python scripts for data preprocessing, training, and evaluation  
- `notebooks/` ? Jupyter notebooks for exploratory analysis and visualizations  
- `data/` ? Input data (ensure compliance with data privacy regulations)  
- `results/` ? ROC curves, evaluation metrics, and interpretation outputs  

## Setup Instructions

1?? Clone the repository:  
```bash
git clone https://github.com/your-username/respiratory-diagnosis.git
cd respiratory-diagnosis

 **Install required Python packages:**  
```bash
pip install -r requirements.txt

```bash
python src/train_model.py
python src/evaluate_model.py

View ROC curves and AUC results in the results/ folder.

