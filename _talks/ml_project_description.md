---
title: "Daily stock price prediction of NIFTY index and various campanies listed in NSE."
collection: talks
type: "Project"
permalink: /talks/ml_project
venue: "Department of Electrical Engineering, IIT Bombay"
date: 2019-05-10
location: "Mumbai, India"
---
[More information here](/images/Project.zip)

* Project description:
  * Processed past 10 years financial data from Yahoo Finance to extract technical indicator features such as RSI,
MASI, and EMA. This project focuses on predicting stock price trend for a company in near future.

  * The prepared dataset looks like the figure shown below .

 <img src="/images/ML_project_data.png"
     alt="Markdown Monster icon" width="600"
     style="float: center; margin-right: 70px;" />
     
  * Proposed Methods:
    * Linear Regression
    * Regression using SVM
    * ANN Regression
    
  * Created Indictor functions:
  
    * Technical indicators use statistical properties of the present and previous samples, so it can be considered as more           related feature as it becomes easy to uptrend and downtrend.
    
    * Technical indicators used:
      * Money Flow Index (MFI)
      * Relative Strength Index (RSI)
        <a href="https://www.codecogs.com/eqnedit.php?latex=100-[100/(1&plus;(Average&space;of&space;upward&space;price&space;change/Average&space;of&space;downward&space;price&space;change))]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?100-[100/(1&plus;(Average&space;of&space;upward&space;price&space;change/Average&space;of&space;downward&space;price&space;change))]" title="100-[100/(1+(Average of upward price change/Average of downward price change))]" /></a>
        
      * Exponential Moving average (EMI)
      * Stochastic Oscillator (SO)
      
  * Evaluated extensive comparisons among the metrics MSE, MAE, and percentage error.
  
  * Implemented different models such as linear regression, support vector regression and ANN.
  * Achieved error rate as low as 0.64% using support vector regression in NIFTY index prediction.
  
The resources for the talk are [here](/images/Presentation-Report.pdf).
