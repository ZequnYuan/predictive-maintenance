# Predictive Maintenance for Industrial Equipment

This repository contains the final project for CS505 - Predictive Maintenance using Machine Learning and Deep Learning.

## 📌 Project Summary

Unexpected machine failures can lead to high maintenance costs and production downtime. This project predicts equipment failure using the NASA C-MAPSS turbofan engine dataset. Multiple models were explored, including:

- Random Forest Classifier
- Support Vector Machines (SVM)
- Long Short-Term Memory (LSTM) Neural Networks

The LSTM model achieved the highest performance, with 91.8% accuracy and a 13.4 RMSE for Remaining Useful Life (RUL) prediction.

## 📁 Files

- `predictive_maintenance.ipynb`: Jupyter Notebook with data preprocessing, model training, and evaluation
- `README.md`: This file
- `train_sample.csv`: A small sample of the C-MAPSS dataset (if allowed)
- `report.docx`: Final project report (upload manually)

## ⚙️ How to Run

1. Clone the repo:
    ```bash
    git clone https://github.com/ZequnYuan/predictive-maintenance
    cd predictive-maintenance
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook predictive_maintenance.ipynb
    ```

## 📊 Results

| Model           | Accuracy | Precision | Recall | F1-score | RMSE (RUL) |
|----------------|----------|-----------|--------|----------|-------------|
| Random Forest  | 88.4%    | 89.9%     | 87.1%  | 88.5%    | -           |
| SVM            | 85.2%    | 83.4%     | 86.5%  | 84.9%    | -           |
| LSTM           | **91.8%**| **92.3%** | **89.0%** | **90.6%** | **13.4**    |

## 📚 Dataset

C-MAPSS dataset provided by NASA:  
https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/

## 📄 License

This project is for academic use only.
