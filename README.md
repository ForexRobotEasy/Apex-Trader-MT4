README:

This README file provides an overview of the code for the Apex Trader MT4. This code is provided by the Forex Robot Easy Team and can be used to implement various trading strategies including mean-reversion, trend-following, and a smart grid system.

To use this code, you will need to include the necessary libraries and define global variables. The code includes the following libraries: Trade.mqh, ArrayObj.mqh, ArrayInt.mqh, and ArrayDouble.mqh. It also includes the CTrade class for executing trading operations.

The code is structured as follows:

1. Global Variables:
   - trade: an instance of the CTrade class for executing trading operations.
   - strategyList: an array to store the list of strategies.
   - meanReversionParams: an array to store the parameters for the mean-reversion strategy.
   - trendFollowingParams: an array to store the parameters for the trend-following strategy.

2. Main Program (OnStart):
   - Initializes the strategy parameters.
   - Checks if the mean-reversion strategy is enabled and applies it if enabled.
   - Checks if the trend-following strategy is enabled and applies it if enabled.
   - Applies the smart grid system.
   - Executes trading operations.
   - Prints the final execution summary.

3. Functions:
   - InitializeStrategyParams: Initializes the strategy parameters for mean-reversion and trend-following.
   - IsMeanReversionEnabled: Checks if the mean-reversion strategy is enabled.
   - IsTrendFollowingEnabled: Checks if the trend-following strategy is enabled.
   - ApplyMeanReversionStrategy: Placeholder function to apply the mean-reversion strategy.
   - ApplyTrendFollowingStrategy: Placeholder function to apply the trend-following strategy.
   - ApplySmartGridSystem: Placeholder function to apply the smart grid system.
   - ExecuteTradingOperations: Placeholder function to execute trading operations.
   - PrintExecutionSummary: Placeholder function to print the final execution summary.

Please note that this code is provided as a sample and Forex Robot Easy is not the official developer of the Apex Trader MT4. For detailed reviews and trading results of this product, you can visit the official developer's site at https://forexroboteasy.com/forex-robot-review/apex-trader-mt4-review-limited-offer-with-free-ea-bonus/. To find the official developer of this product, please refer to MQL5.
