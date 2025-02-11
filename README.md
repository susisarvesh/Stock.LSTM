# Stock Price Prediction Using Prophet and LSTM  

This project combines the predictive capabilities of **Prophet** and **LSTM (Long Short-Term Memory)** models to forecast stock prices. It integrates sequential data processing from LSTM with the robust forecasting features of Prophet, providing a comprehensive method for financial analysis and prediction.  

## Features  
- **Data Preprocessing**:  
  Fetch and prepare historical stock data using `yfinance`.  

- **Prophet Model**:  
  - Forecasts stock prices for the next 365 days.  
  - Interactive visualizations using `Plotly`.  

- **LSTM Model**:  
  - Splits data into training and testing sets.  
  - Scales data for better model performance.  
  - Predicts closing prices and evaluates using Root Mean Squared Error (RMSE).  
  - Compares real vs. predicted prices with visualizations.  

- **Streamlit Integration**:  
  - User-friendly interface with sliders for interaction.  
  - Efficient data caching for smoother performance.  

## Technologies Used  
- **Python Libraries**:  
  - `Streamlit`  
  - `Pandas`  
  - `NumPy`  
  - `TensorFlow` (Keras)  
  - `yfinance`  
  - `Prophet`  
  - `Plotly`  

## Installation  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/susisarvesh/Stock.LSTM.git  
   cd Stock.LSTM  


2. **Set Up a Python Environment** (Optional but Recommended):  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # On Windows: venv\Scripts\activate  
   ```  

3. **Install Dependencies**:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. **Run the Application**:  
   ```bash  
   streamlit run app.py  
   ```  

5. **Access the App**:  
   Open the URL displayed in the terminal (usually `http://localhost:8501`).  

## Example Usage  
1. Enter the stock ticker symbol (e.g., `AAPL` for Apple).  
2. View the Prophet model's forecast for the next 365 days.  
3. Analyze LSTM predictions for closing prices with performance metrics like RMSE.  
4. Compare real vs. predicted prices using interactive `Plotly` charts.  

## Key Insights  
This project highlights how combining Prophet and LSTM models enhances stock price forecasting by leveraging their individual strengths:  
- **Prophet** excels at capturing trends and seasonality.  
- **LSTM** processes sequential data effectively for accurate predictions.  

## Disclaimer  
This project is for educational purposes only. Stock market predictions made using machine learning models should be supplemented with professional advice and thorough analysis.  

## Contributions  
Contributions are welcome! If you find a bug or have a feature request, feel free to open an issue or create a pull request.  

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---

**Keywords**: Streamlit, Pandas, NumPy, Keras (TensorFlow), yfinance, Prophet (Facebook), Plotly, LSTM, Slider (UI interaction), Data caching.  
```
## Conference Paper

[Download Conference Paper 370 (Final)](https://ik.imagekit.io/imagespath/Conference%20Paper%20370%20Final.docx?updatedAt=1739293594265)

