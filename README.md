markdown
TJR Strategy - Streamlit App

This app implements the *TJR strategy* on EUR/USD vs GBP/USD forex pairs using real-time data from Yahoo Finance. It identifies Buy/Sell signals based on SMT Divergence, Break of Market Structure (BMS), and Fair Value Gap (FVG).

Features

- Live 60-day 1-hour interval data
- Signal generation based on TJR strategy
- Buy/Sell markers on EUR/USD chart
- Signal export to `tjr_signals.csv`
- Interactive Streamlit UI

Setup Instructions

1. Clone or download the repo.
2. Install dependencies:

bash
pip install -r requirements.txt


3. Run the app:

bash
streamlit run app.py


4. A browser window will open showing the app interface.

Output

- Chart with price and Buy/Sell signals
- Table of last 10 signal rows
- `tjr_signals.csv` file containing signal history

Author

Built with ❤️ using Python, Pandas, Matplotlib, and Streamlit.

