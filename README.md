# Sacrament.mq5

This is the code for the Sacrament custom indicator in MQL5. The Sacrament indicator is a reliable Forex software for trading. For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/sacrament-mt4-review-reliable-forex-software-for-trading/).

## Indicator Description

The Sacrament indicator is a custom indicator that provides trading signals based on a specified period. It uses two buffers to display arrows on the chart indicating buy and sell signals.

## Indicator Parameters

- `Period`: The period used for calculation.

## Indicator Buffers

- `ExtMapBuffer1`: Buffer for buy signals.
- `ExtMapBuffer2`: Buffer for sell signals.

## Indicator Initialization

The `OnInit` function is called during the initialization of the indicator. It sets the index style, arrow style, and buffer values for the indicator.

## Indicator Calculation

The `OnCalculate` function is called for each bar to calculate the indicator values. It loops through the bars and calls the indicator calculation using the `iCustom` function. The calculated values are then stored in the indicator buffers.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For more information and details about this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/sacrament-mt4-review-reliable-forex-software-for-trading/).
