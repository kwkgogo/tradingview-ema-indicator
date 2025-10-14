# TradingView EMA 9/21/50 Indicator

A customizable TradingView Pine Script indicator that displays three Exponential Moving Averages (9, 21, and 50) with cross alerts and visualization options.

## Features

- **Three EMAs**: 9, 21, and 50 periods
- **Customizable Display**: Toggle visibility of each EMA independently
- **Cross Detection**: Automatically detects when EMA 9 crosses EMA 21 or EMA 50
- **Visual Labels**: Shows labels at cross points for easy identification
- **Alerts**: Built-in alert conditions for EMA crosses

## Installation

1. Open TradingView chart
2. Click on "Indicators" button
3. Click "Pine Editor" at the bottom
4. Copy the code from `EMA-9-21-50.pine`
5. Click "Add to Chart"

## Usage

### Display Settings

You can customize which EMAs to display:
- **Show EMA 9** (Yellow): Short-term trend
- **Show EMA 21** (Blue): Medium-term trend
- **Show EMA 50** (Red): Long-term trend
- **Show Cross Labels**: Toggle labels that appear when EMAs cross

### Alert Conditions

The indicator includes four alert conditions:
1. EMA 9 crosses above EMA 21
2. EMA 9 crosses below EMA 21
3. EMA 9 crosses above EMA 50
4. EMA 9 crosses below EMA 50

To set up alerts:
1. Click the "Alerts" button (clock icon)
2. Select "EMA 9/21/50" as the indicator
3. Choose your desired condition
4. Configure alert delivery method

## Interpretation

- **Bullish Signal**: When EMA 9 crosses above EMA 21 or EMA 50
- **Bearish Signal**: When EMA 9 crosses below EMA 21 or EMA 50
- **Trend Confirmation**: All three EMAs aligned (9 > 21 > 50 for uptrend, reverse for downtrend)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Disclaimer

This indicator is for educational and informational purposes only. It should not be considered financial advice. Always do your own research and consult with a financial advisor before making investment decisions.
