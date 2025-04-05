# Stockify - Virtual Trading Platform

Stockify is a Python-based virtual trading platform designed for stock market simulation and analysis. It enables users to place simulated trades, analyze market trends, and evaluate trading strategies in a risk-free environment. Built with Python, Flask, Pandas, and Streamlit, Stockify provides real-time market data visualization and portfolio tracking.

## Features
- **Stock Price Prediction**: Website which can be used to predict stock prices.
- **Interactive User Interface**: User-friendly and responsive UI built with **Streamlit**.
- **Scalable Architecture**: RESTful API-based modular design.
- **Real-Time Market Data**: Fetch and visualize stock data using external APIs (e.g., Yahoo Finance, Alpha Vantage).
- **Portfolio Management**: Track virtual assets and trade performance.
- **Live Charting**: Interactive stock charts for real-time trend analysis.
- **Paper Trading Mode**: Simulated trading with no real money involved.

## Tech Stack
- **Frontend**: Streamlit (for interactive UI)
- **Backend**: Flask (for API handling)
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly
- **Stock Data**: Yahoo Finance API, NSE API
- **Authentication**: Flask-Login (for user authentication)

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Python (3.10+)
- pip (latest version)
- Virtual environment (optional but recommended)

### Steps
1. **Clone the repository:**
   ```sh
   git clone https://github.com/manojkumar9911/stockify.git
   cd stockify
   ```
2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Set up environment variables:**
   Create a `.env` file in the project root and add:
   ```env
   FLASK_APP=app.py
   FLASK_ENV=development
   API_KEY=your_api_key_here
   ```
   Replace `your_api_key_here` with your stock market API key (Yahoo Finance or Alpha Vantage).

5. **Run the application:**
   ```sh
   streamlit run app.py
   ```
   The application will be available at `http://localhost:8501`.

## Usage
1. **Navigate to the platform:** Open `http://localhost:8501` in your browser.
2. **Search for a stock:** Enter the stock ticker to fetch real-time data.
3. **Analyze stock trends:** View historical stock prices with interactive charts.
4. **Simulate trades:** Buy/sell stocks in virtual trading mode.
5. **Monitor portfolio:** Track profit/loss from simulated trades.

## Future Enhancements
- **AI-based Trading Strategies**: Implement deep learning models for strategy recommendations.
- **Live WebSocket Integration**: Real-time price updates via WebSockets.
- **User Authentication & Profiles**: Track trading history for individual users.
- **Advanced Risk Analysis**: Volatility prediction and risk assessment tools.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit changes and push to your fork.
4. Submit a pull request.

## Contact
- **Author:** Manoj Kumar Sial  
- **Email:** manojkumarsial2002@gmail.com  
- **GitHub:** [github.com/manojkumar9911](https://github.com/manojkumar9911)  
- **LinkedIn:** [linkedin.com/in/manoj-kumar-sial](https://www.linkedin.com/in/manoj-kumar-sial/)  

**Let's collaborate and build something awesome! 🚀**

## License
This project is licensed under the MIT License.

