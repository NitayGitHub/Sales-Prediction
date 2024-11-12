# Sales Prediction
## **Introduction**
This project uses machine learning to predict sales, leveraging XGBoost and Random Forest algorithms for accurate forecasting. By analyzing historical sales data, the model learns patterns and trends to project future demand. This code covers data preprocessing, model training, and evaluation, offering a reliable approach to sales prediction.

## **Installation**

This project is run on Kaggle instead of Google Colab. Before running the code, ensure that the following libraries are pre-installed:

- **Torch**: For deep learning support and model training.
- **Sklearn**: For various machine learning utilities and metrics.
- **Pandas**: For data manipulation and analysis.
- **Numpy**: For numerical computations and array handling.

To install these libraries, you can use the following command:

```python
!pip install torch scikit-learn pandas numpy
```

## **Data Sources**
The sales data for this project was downloaded from [Sales Prediction Dataset](https://www.kaggle.com/datasets/mohdshahnawazaadil/sales-prediction-dataset).

## **Training Results**

| Model          | Mean Absolute Error | R-Squared |
|----------------|---------------------|-----------|
| XGBoost        | 734                 | 0.99      |
| Random Forest  | 1800                | 0.93      |

In addition, training shows that 'credit card debt' doesn't help to predict 'car purchase amount' and that 'age' is the most importent feature.
