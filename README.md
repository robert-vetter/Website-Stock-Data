# Website Stock Data

![Stock Data](https://img.shields.io/badge/Status-Active-brightgreen.svg) ![License](https://img.shields.io/badge/License-MIT-blue.svg)

## 📌 Overview
This repository provides stock market data retrieved from the **Alpha Vantage API** for use in the portfolio website [stock-prediction.rvetter.com](https://stock-prediction.rvetter.com). The dataset supports financial analysis and stock prediction features on the website.

## 🚀 Features
- Fetches real-time and historical stock data from **Alpha Vantage API**.
- Supports multiple stock symbols for comparative analysis.
- Optimized for integration with **stock-prediction.rvetter.com**.
- Designed for scalability and maintainability.

## 🛠️ Installation & Setup
### Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.8+
- `requests` library for API calls

### Installation
Clone this repository:
```sh
$ git clone https://github.com/your-username/Website-Stock-Data.git
$ cd Website-Stock-Data
```

Install dependencies:
```sh
$ pip install -r requirements.txt
```

## 🔧 Usage
1. Obtain an API key from [Alpha Vantage](https://www.alphavantage.co/support/#api-key).
2. Create a `.env` file and store your API key:
   ```sh
   ALPHA_VANTAGE_API_KEY=your_api_key_here
   ```
3. Run the script to fetch stock data:
   ```sh
   python fetch_stock_data.py --symbol AAPL --output data.json
   ```

## 📈 Example Output
```json
{
  "symbol": "AAPL",
  "price": 176.15,
  "volume": 52348100,
  "timestamp": "2025-03-05T16:00:00Z"
}
```

## 🤝 Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## 📜 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## 📞 Contact
For any inquiries, feel free to reach out:
- **GitHub**: [your-username](https://github.com/your-username)
- **Website**: [rvetter.com](https://rvetter.com)
