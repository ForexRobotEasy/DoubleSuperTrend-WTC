# DoubleSuperTrend WTC

This code is a sample implementation of the DoubleSuperTrend indicator in MQL5. It is developed by the Forex Robot Easy Team and can be used to enhance the accuracy of forex trading.

## How it Works

The DoubleSuperTrend indicator is a trend-following indicator that helps identify the direction of the market trend. It uses a combination of two SuperTrend indicators to generate trading signals.

The code includes the necessary libraries and headers to import the Trade and DoubleSuperTrend classes. The constants LOT_SIZE, STOP_LOSS, and TAKE_PROFIT are defined to set the parameters for the trades.

The objects trade and doubleSuperTrend are initialized to create instances of the Trade and DoubleSuperTrend classes, respectively.

The function ExecuteTrade is defined to execute the trades based on the direction of the trend. It calculates the stop loss and take profit levels based on the current bid and ask prices. The trade.BuyStop and trade.SellStop functions are used to place the buy and sell orders, respectively.

The function CheckTrendAndTrade is defined to check the current trend using the doubleSuperTrend.CheckTrend method. If the trend is up, the ExecuteTrade function is called with the BUY action. If the trend is down, the ExecuteTrade function is called with the SELL action.

In the OnStart function, the DoubleSuperTrend indicator is set up by calling the doubleSuperTrend.Init method. The trend color cloud feature is enabled by calling the doubleSuperTrend.SetColorCloud method. Then, the CheckTrendAndTrade function is called to check the trend and execute trades.

In the OnTick function, the DoubleSuperTrend indicator is updated by calling the doubleSuperTrend.Update method. Then, the CheckTrendAndTrade function is called to check the trend and execute trades based on any changes in the trend.

## Product Description

DoubleSuperTrend WTC is a powerful forex trading indicator developed by the Forex Robot Easy Team. It enhances the accuracy of forex trading by identifying the direction of the market trend and generating trading signals based on the DoubleSuperTrend indicator.

This code provides a sample implementation of the DoubleSuperTrend indicator in MQL5. It can be used as a reference to understand how the indicator works and to develop your own trading strategies based on the indicator.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in the product. For detailed reviews and trading results of this product, please visit the official developer's website at [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/doublesupertrend-wtc-review-enhance-forex-trading-accuracy/).

To find the official developer of this product and to purchase the full version, please visit the MQL5 website.
