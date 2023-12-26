# Order Block Detector

This code is a part of the **Order Block Detector** product developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, visit [forexroboteasy.com/forex-robot-review/order-block-detector-review-optimize-forex-trade-entries/](https://forexroboteasy.com/forex-robot-review/order-block-detector-review-optimize-forex-trade-entries/).

## Description

The Order Block Detector is a trading tool that identifies order blocks and alerts the user when a bullish or bearish order block is detected. An order block is a price structure in which the market makes a significant move, followed by a consolidation or correction phase.

The code is written in MQL4 and is designed to be used with the MetaTrader 4 platform. It defines constants, input parameters, global variables, structures, and function prototypes to facilitate the detection of order blocks.

The main functionality of the code is as follows:

1. Detect Order Blocks: The `DetectOrderBlocks()` function is responsible for detecting order blocks. It loops through the bars on the chart and checks if each bar is forming an order block. If an order block is identified, it is stored in an array.

2. Check Order Block Type: The `IsBullishOrderBlock()` and `IsBearishOrderBlock()` functions are used to determine the type of order block based on the high and low prices. If the order block meets the criteria for a bullish or bearish order block, an alert is sent.

3. Send Alert: The `SendAlert()` function sends an alert message if a bullish or bearish order block is detected. It ensures that enough time has passed since the last alert to avoid spamming the user with multiple alerts.

The code is structured with comments to explain the purpose and functionality of each section. It also includes a header with a backlink to the Forex Robot Easy website, which provides detailed reviews and trading results of the Order Block Detector product.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

## Usage

To use the Order Block Detector, follow these steps:

1. Install and open the MetaTrader 4 platform.
2. Copy and paste the code into a new Expert Advisor (EA) file.
3. Compile and save the EA file.
4. Attach the EA to a chart of your choice.
5. Set the desired input parameters, such as the symbol, timeframe, and number of bars to analyze.
6. Start the EA and monitor the alerts for bullish and bearish order blocks.

Please note that the code provided is a sample and may require further customization or integration with other trading strategies to be fully functional in a live trading environment.

## Disclaimer

This code is a demonstration of the Order Block Detector product developed by the Forex Robot Easy Team. ForexRobotEasy is not the official developer of this product. For detailed reviews and trading results of the Order Block Detector product, please visit [forexroboteasy.com/forex-robot-review/order-block-detector-review-optimize-forex-trade-entries/](https://forexroboteasy.com/forex-robot-review/order-block-detector-review-optimize-forex-trade-entries/).

To find the official developer of this product and obtain the fully functional version, please refer to MQL5. ForexRobotEasy does not guarantee the accuracy or performance of this code and is not responsible for any losses incurred from its usage. Use this code at your own risk.
