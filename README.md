# Gold Miner 46

Code developed by Forex Robot Easy Team

Website: [forexroboteasy.com](https://forexroboteasy.com)

For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/gold-miner-46-review-optimal-buy-settings-for-forex-success/).

## Description

Gold Miner 46 is a trading robot that aims to optimize buy settings for successful forex trading. This code is a sample implementation of the trading strategy used by Gold Miner 46. Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## How It Works

The code utilizes several global variables to control the trading process:

- `highestPrice`: Stores the highest price reached during the trading session.
- `currentPrice`: Stores the current price of the market.
- `dipThreshold`: Defines the threshold below which a buy order should be initiated.
- `buyAmount`: Specifies the amount to buy when a buy order is placed.

The code consists of three main functions:

1. `BuyInitiation()`: Initiates a buy order when the current price dips below the dip threshold. It uses the `OrderSend()` function to place the buy order.
2. `ContinueBuying()`: Continues buying as the price decreases further. It places another buy order if the current price is below the `highestPrice`.
3. `StopBuying()`: Stops buying when the price reaches the highest setting. This function should be customized to handle the process of stopping the buying.

The entry point of the program is the `OnTick()` function. It performs the following steps:

1. Retrieves the current price using the `MarketInfo()` function.
2. Calls the `BuyInitiation()` function to check if a buy order should be initiated.
3. Calls the `ContinueBuying()` function to check if another buy order should be placed.
4. Calls the `StopBuying()` function to check if buying should be stopped.

Please note that this code is a simplified version of the trading strategy used by Gold Miner 46. The official developer of this product may have implemented additional features and optimizations.

For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/gold-miner-46-review-optimal-buy-settings-for-forex-success/).
