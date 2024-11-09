# Stock Market Visualizer 📈

A Python desktop application that allows users to visualize stock market data with an intuitive graphical interface. Built with tkinter for the GUI and leveraging yfinance for real-time stock data retrieval.

## Features 🌟

- **Interactive Date Selection**: 
  - Custom date range picker
  - Quick presets (1 month, 3 months, 6 months, 1 year)
  - Date validation and error handling
  - Support for up to 15 years of historical data

- **Flexible Visualization Options**:
  - Candlestick charts with volume indicators
  - Dark and light themes
  - Automatic scaling and formatting
  - Real-time data fetching from Yahoo Finance

- **User-Friendly Interface**:
  - Clean and intuitive GUI
  - Form validation and error messaging
  - Easy-to-use controls
  - Quick reset functionality

## Technical Details 🔧

### Dependencies
- `tkinter`: GUI framework
- `tkcalendar`: Calendar widget for date selection
- `yfinance`: Stock market data API
- `pandas`: Data manipulation
- `matplotlib`: Basic plotting functionality
- `mplfinance`: Specialized financial charts

## Usage 💻

1. Enter a stock symbol (e.g., MSFT, AAPL)
2. Select a date range:
   - Use quick presets OR
   - Choose custom start and end dates
3. Select preferred theme (light/dark)
4. Click "Visualize" to generate the chart
5. Use "Clear" to reset all inputs


## Error Handling 🛡️

- Date validation for realistic ranges
- Network and API error handling
- Invalid symbol detection
- Empty data handling
- User input validation

## Future Enhancements 🔮

- Additional technical indicators
- Multiple stock comparison
- Export functionality for charts
- Custom indicator settings
- Portfolio tracking features
