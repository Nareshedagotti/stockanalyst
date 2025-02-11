# TradeWise AI - Smart Trading Companion 🚀

TradeWise AI is a **Streamlit-based web application** that helps traders analyze stock data, visualize trends, and generate AI-powered forecasts. It integrates **Yahoo Finance** for real-time stock data, **Ollama DeepSeek-R1** for AI-driven insights, and **Plotly** for interactive visualizations.

---

## Features ✨

- **Real-time Stock Analysis**:
  - Fetch and analyze stock data for Indian and global markets.
  - AI-powered technical analysis with actionable insights.

- **Advanced Visualization**:
  - Interactive candlestick charts.
  - Moving averages and volume analysis.

- **AI Forecasting**:
  - Predict future stock prices using linear regression.
  - Generate trading strategies and risk assessments.

- **User-Friendly Interface**:
  - Sidebar navigation for easy access to features.
  - Clean and intuitive design.

---

## Tech Stack 🛠️

- **Frontend**: Streamlit
- **Backend**: Python
- **AI Model**: Ollama DeepSeek-R1
- **Data Source**: Yahoo Finance (`yfinance`)
- **Visualization**: Plotly

---

## Installation 🛠️

### Prerequisites

- Python 3.8 or higher
- Ollama (for running DeepSeek-R1 locally)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Nareshedagotti/stockanalyst.git
   cd stockanalyst
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Ollama**:
   - Download and install Ollama from [ollama.ai](https://ollama.ai/).
   - Run the DeepSeek-R1 model:
     ```bash
     ollama run deepseek-r1
     ```

5. **Run the Application**:
   ```bash
   streamlit run main.py
   ```

6. **Access the App**:
   - Open your browser and go to `http://localhost:8501`.

---

## Usage 🚀

1. **Enter a Stock Ticker**:
   - Use the format `TICKER.NS` for Indian stocks (e.g., `SBIN.NS` for SBI).
   - Use `TICKER` for global stocks (e.g., `AAPL` for Apple).

2. **Select Analysis Mode**:
   - **Real-time Analysis**: Get AI-powered insights and technical analysis.
   - **Visualization**: View interactive charts and technical indicators.
   - **Forecasting**: Predict future stock prices and generate trading strategies.

3. **Adjust Settings**:
   - Use the sidebar to select the analysis period and forecast days.

4. **Explore Results**:
   - View AI-generated forecasts, charts, and recommendations.

---

## Project Structure 📂

```
tradewise-ai/
├── app/
│   ├── main.py            # Main application
│   ├── analysis.py        # Stock analysis functions
│   ├── visualization.py   # Visualization components
│   ├── forecasting.py     # Forecasting functions
│   └── utils.py           # Utility functions
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## Example Queries 💡

- **Analyze a Stock**:
  - "Analyze SBIN.NS and provide a trading strategy."
  
- **Compare Stocks**:
  - "Compare SBIN.NS and HDFCBANK.NS for the last 30 days."

- **Forecast Prices**:
  - "Predict the price of NESTLEIND.NS for the next 30 days."

---

## Screenshots 📸

### Real-time Analysis
![Real-time Analysis](screenshots/analysis.png)

### Advanced Visualization
![Advanced Visualization](screenshots/visualization.png)

### AI Forecasting
![AI Forecasting](screenshots/forecasting.png)

---

## Contributing 🤝

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

---

## Acknowledgments 

- **Yahoo Finance** for providing real-time stock data.
- **Ollama** for the DeepSeek-R1 model.
- **Streamlit** for the amazing web app framework.

