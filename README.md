# Stock Price Analysis & Prediction Using an LSTM model (RNN) with Tensorflow Backend

Stock analysis is a method for investors and traders to make buying and selling decisions. By studying and evaluating past and current data, investors and traders attempts to gain an edge in the markets by making informed decisions. Stock market prediction and analysis is a classic problem which has been analyzed extensively using tools and techniques of Machine Learning. Forecasting stock market prices has always been challenging task for many business analysts and researchers. In fact, stock market price prediction is an interesting area of research for investors. For successful investment lot many investors are interested in knowing about future situation of market. Effective prediction systems indirectly help traders by providing supportive information such as the future market direction. Data mining techniques are effective for forecasting future by applying various algorithms over data.

Technical Analysis:

Technical analysts evaluate recent trading movements and trends to attempt to determine what’s next for a company’s stock price. Generally, technical analysts pay less attention to the fundamentals underlying the stock price. Technical analysts rely on stock charts to make their assessment of a company’s stock price. For example, technicians may look for a support level and resistance level when assessing a stock’s next move. A support level is a price level at which the stock might find support and below which it may not fall. In contrast, a resistance level is a price at which the stock might find pressure and above which it may not rise.

Assumption in Technical Analysis are unlike fundamental analysts, technical analysts don’t care whether a stock is undervalued or overvalued. In fact the only thing that matters is the stocks past trading data (price and volume) and what information this data can provide about the future movement in the security.

LSTM MODEL:

Learning to store information over extended time intervals via recurrent back propagation takes a very long time, mostly due to insufficient, decaying error back flow.LSTM can learn to bridge minimal time lags in excess of 1000 discrete time steps by enforcing constant error flow through \constant error carrousels" within special units. Multiplicative gate units learn to open and close access to the constant error flow. LSTM is local in space and time; its computational complexity per time step and weight is O(1). 

To reduce the vanishing (and exploding) gradient problem, and therefore allow deeper networks and recurrent neural networks to perform well in practical settings, there needs to be a way to reduce the multiplication of gradients which are less than zero. The LSTM cell is a specifically designed unit of logic that will help reduce the vanishing gradient problem sufficiently to make recurrent neural networks more useful for long-term memory tasks i.e. text sequence predictions. The way it does so is by creating an internal memory state which is simply added to the processed input, which greatly reduces the multiplicative effect of small gradients. 

The time dependence and effects of previous inputs are controlled by an interesting concept called a forget gate, which determines which states are remembered or forgotten. Two other gates, the input gate and output gate, are also featured in LSTM cells.


Technical Analysis for Stock Growth Prediction based on factors :

RSI:

The relative strength index (RSI) is a momentum indicator developed by noted technical analyst Welles Wilder, that compares the magnitude of recent gains and losses over a specified time period to measure speed and change of price movements of a security.

The relative strength index is calculated using the following formula:
RSI = 100 - 100 / (1 + RS)


EMA:

An exponential moving average (EMA) is a type of moving average that is similar to a simple moving average, except that more weight is given to the latest data. It's also known as the exponentially weighted moving average.

MACD:

Moving average convergence divergence (MACD) is a trend-following momentum indicator that shows the relationship between two moving averages of prices.

The MACD is calculated by subtracting the 26-day exponential moving average (EMA) from the 12-day EMA.

ROC:

The rate of change - ROC - is the speed at which a variable changes over a specific period of time. ROC is often used when speaking about momentum, and it can generally be expressed as a ratio between a change in one variable relative to a corresponding change in another.

ROC = {(current value / previous value) - 1} x 100.

