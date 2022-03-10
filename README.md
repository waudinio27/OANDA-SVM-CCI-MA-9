# OANDA-SVM-CCI-MA-9
Support Vector Machines with Momentum Indicators

Hello Everybody.

This is a proper Support Vector Machines Bot that I developed all by myself.
The main idea behind it is to smooth out the price data with a Moving Average. In this example, it is with a period of 9, but 5 will also work out well.
After this, Momentum Indicators are built with TA-lib and the smoothed out data, and are applied to the prediction task.
Like this, the SVM has no problems with the classification at all and achieves high accuracy. The hyperplane can be built in a good way.

Right now, the backtest still has issues, like missing transaction costs among other things. Also, one will probably need to run the algorithm in the cloud or from a Raspberry Pi to achieve good results.

If somebody finds a way to improve the algo, please contact me for cooperation by mail. 
