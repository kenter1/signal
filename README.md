Signal
==============

kenter1

included yaml file for dependencies

Convolutional Neural Network 
----------------------------

Description
----------------------------------
Trained on stocks candlestick plot images using a convolutional net.
Gives a signal whether a certain candlestick plot image will move 1% upward or 1% downward
Used 2004-2008 for training then 2009 for backtest

Backtesting uses simple trading algorithm
  Increase position or decrease position by 1 if there is a signal
  If there is no signal take profit if possible.

