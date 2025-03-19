# Data-Energy-Consumption-Forecasting

## Brief Overview
This project offers an interactive solution for predicting average daily energy consumption while providing insights into consumer behavior. By combining a **Seasonal Autoregressive Integrated Moving Average (SARIMAX)** model with a **Streamlit** dashboard, users can explore energy consumption patterns and anticipate future demand trends.

## Data Sourcing And Cleaning
The original dataset included inconsistencies. To address this, the total daily energy consumption was averaged based on the number of contributing households. This approach ensured a more reliable representation of overall community energy usage patterns.

## Insights and Visualizations
The **Streamlit** dashboard delivers a suite of insightful visualizations:  
- 📊 Comparative analysis of energy consumption on **holidays vs. non-holidays**.  
- 📈 Distribution of average daily energy consumption through **interactive histograms**.  
- 🌡️ Correlation between energy usage and environmental factors like **temperature**, **humidity**, and **wind speed**.  
- 🔍 **Clustering** of households to identify different energy usage behaviors.  
- 📉 **Forecast vs. actual** energy consumption with RMSE evaluation metrics.  
- 💰 **Cost predictions** based on forecasted energy consumption.  

## Technologies Used
- 🐍 Python  
- 📦 SARIMAX (Statsmodels)  
- 🐼 Pandas  
- 🔢 NumPy  
- 🌐 Streamlit  
- 📊 Plotly  

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
