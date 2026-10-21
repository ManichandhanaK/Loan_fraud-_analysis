**AI-Powered Stock Price Prediction and Analysis**
An AI system for forecasting stock prices and generating buy/hold/sell recommendations using LSTM deep learning and real-time financial news integration.

🚀 Features
LSTM model trained on historical stock data (Yahoo Finance API via yfinance).
Real-time news fetching using LangChain + SerpAPI.
Market insight summarization using Gemini API.
Interactive Streamlit dashboard with predictions, recommendations, and news.
🛠️ Tech Stack
Python, Pandas, Numpy, Scikit-learn
TensorFlow/Keras (LSTM)
yfinance, LangChain, SerpAPI
Gemini API (Google Generative AI)
Streamlit, Plotly
⚙️ Setup
git clone https://github.com/sreyojyotiray/ai-stock-forecast.git
cd ai-stock-forecast
pip install -r requirements.txt
Set API keys:

export SERPAPI_API_KEY="your_serpapi_key"
export GEMINI_API_KEY="your_gemini_key"
Run:

streamlit run src/app.py
⚠️ Disclaimer
This project is for educational purposes only.
It is not financial advice. Always do your own research before making investment decisions.
