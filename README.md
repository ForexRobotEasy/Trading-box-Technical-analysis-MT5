# Trading box Technical analysis MT5

This code is a custom indicator for technical analysis in MetaTrader 5 platform. It provides functionality to draw supply and demand zones, support and resistance levels, and set price alerts.

## Features

- Supply and Demand Zones: The indicator can draw rectangles to represent supply and demand zones. These zones are defined by the highest and lowest prices and the start and end times.
- Support and Resistance Levels: The indicator can draw trendlines to mark support and resistance levels. These levels are defined by a specific price and the start and end times.
- Price Alerts: The indicator can set price alert levels based on the current and previous prices. It checks for price crossing these levels and triggers an alert when a crossing occurs.

## Usage

To use this indicator, follow these steps:

1. Install MetaTrader 5 platform and open the desired chart.
2. Go to the 'Navigator' window and expand the 'Indicators' section.
3. Right-click on the 'Custom Indicators' folder and select 'Refresh' to update the list.
4. Locate the 'Trading box Technical analysis MT5' indicator and drag it onto the chart.
5. Set the desired inputs for the indicator, such as the buffer size for price alerts and the colors for supply and demand zones and support and resistance levels.
6. The indicator will automatically draw supply and demand zones and support and resistance levels on the chart. It will also check for price alerts and trigger alerts when a crossing occurs.

## Customization

The code allows customization through the following input variables:

- `alertBuffer`: Specifies the buffer size for price alerts. It determines the distance from the previous price at which an alert will be triggered.
- `supplyDemandColor`: Specifies the color for supply and demand zones.
- `supportResistanceColor`: Specifies the color for support and resistance levels.

## Disclaimer

This code is provided as a sample and demonstration of how the Trading Box MT5 indicator works. Forex Robot Easy is not the official developer of this product. For detailed reviews and trading results of the official product, please visit [Forex Robot Easy - Trading Box MT5 Review](https://forexroboteasy.com/forex-robot-review/trading-box-mt5-review-all-in-one-forex-technical-analysis-tool/). To find the official developer of this product, please refer to MQL5.
