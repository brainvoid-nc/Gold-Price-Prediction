# Gold Price Prediction

This project aims to predict the price of gold using various machine learning models. The analysis covers a decade of data and utilizes advanced predictive techniques to provide accurate forecasts.

## Table of Contents

- [Introduction](#introduction)
- [Models Used](#models-used)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Enhancements](#future-enhancements)
- [References](#references)

## Introduction

Gold has been a valuable asset for centuries, serving not only as a medium of exchange but also as a reliable investment. This project focuses on predicting gold prices by analyzing historical data and applying machine learning models to forecast future trends.

## Models Used

- **Linear Regression**
- **Decision Trees**
- **Random Forests**

Among these, the Random Forest method provided the most accurate results due to its ability to handle multiple factors and complex interactions in the data.

## Dataset

The dataset used for this project was sourced from Kaggle and includes:

- A decade of data (2008-2018)
- Attributes such as date, opening and closing stock prices, high and low prices, adjusted close prices, and volume
- Comparative data for other financial indicators like the S&P 500 index, USD rates, and Silver ETF prices

## Methodology

1. **Data Collection**: 
   - Data was collected from Kaggle, encompassing various financial attributes over ten years.
2. **Data Preprocessing**: 
   - Cleaning and preprocessing steps were implemented to handle missing values and irrelevant attributes.
3. **Data Splitting**:
   - The dataset was split into training (70%) and testing (30%) sets to evaluate the model performance.
4. **Model Training**: 
   - Different machine learning models were trained on the dataset.
5. **Model Evaluation**: 
   - Models were evaluated based on their predictive accuracy and other performance metrics.

## Results

- **Correlation Analysis**: A heatmap was used to understand the correlations between different financial indicators and gold prices.
- **Model Performance**: The Random Forest model outperformed other models, providing the highest prediction accuracy.

## Conclusion

Predicting gold prices is a complex task influenced by various economic factors. The Random Forest model demonstrated superior performance in capturing these complexities, making it a reliable tool for forecasting gold prices.

## Future Enhancements

- Incorporating additional financial indicators to improve prediction accuracy.
- Applying deep learning techniques for more robust predictions.
- Expanding the dataset to include more recent data for better model training.

## References

[1] D. G. Navin, "Big Data Analytics for Gold Price Forecasting Based on 
Decision Tree Algorithm and Support Vector," International Journal of Science 
and Research, pp. 2026-2030, 2015.  
[2] M. S. S. S. S. Kumar Chandar, "Forecasting Gold Prices Based on Extreme 
Learning Machine," International Journal of Computers Communications & 
Control, pp. 372-380, 2016.  
[3] Shafiee,Shahriar and Erkan Topal. An overview of global gold market and 
gold price forecasting. Resources Policy .Volume:35, 2010 
[4] For DATASET-- https://www.kaggle.com/datasets/altruistdelhite04/gold
price-data

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gold-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd gold-price-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the model training script:
   ```bash
   python train_model.py
   ```

For more detailed instructions, please refer to the `train_model.py` script and the comments within the code.

