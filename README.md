# Price Pilot - Market Price Forecasting System 

A comprehensive web application that scrapes real-time product prices from major e-commerce platforms and predicts future price trends using advanced time series analysis.

## Features

- **Multi-Platform Price Scraping**: Automatically extracts product prices from 4 major e-commerce platforms
  - Flipkart
  - Amazon India  
  - Nykaa
  - Myntra
- **Real-Time Data Collection**: Fetches current product prices and information
- **Price Trend Forecasting**: Uses ARIMA time series modeling to predict future price movements
- **Interactive Web Interface**: User-friendly Gradio-based web app for easy product search
- **Synthetic Historical Data**: Generates realistic price history when actual historical data isn't available
- **Visual Analytics**: Price comparison charts and forecasting visualizations

##  Technologies Used

- **Python 3.x**
- **Selenium WebDriver** - Browser automation for dynamic content scraping
- **pmdarima** - Automated ARIMA model selection and forecasting
- **scikit-learn** - Data preprocessing and scaling
- **Pandas & NumPy** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Gradio** - Web interface framework
- **BeautifulSoup** - HTML parsing (backup scraping method)

