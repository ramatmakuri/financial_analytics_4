# Financial Analytics - Investment Analysis
____


The program evaluates four new investment options for inclusion in the client portfolios. The program determines the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

## Packages Used
This project leverages python 3.7

## Installation Guide
The application requires the below programs to be installed

* python
* pandas 
* pathjlib 
* matplotlib 
* numpy

## Project functionality and Examples of Usage:
The project begins with importing the performance of four major fund managers in csv fomat.  

The program consist of 3 phases:

1. Analyze the performacne of the funds vis-a-vis each other and the markey represented by S&P 500 ETF (SPY - hereinafter referred to as market) - Performance is analyzed by calculating and comparing the daily returns and cumulative returns earned by the 4 funds and the market
<img width="863" alt="Screen Shot 2022-01-29 at 10 06 47 PM" src="https://user-images.githubusercontent.com/96159292/151688747-5cb449f7-31f5-40b5-98b6-cf4ac7d4c692.png">

2. Volatility of the returns is analyzed using box plots.
<img width="1097" alt="Screen Shot 2022-01-29 at 10 07 50 PM" src="https://user-images.githubusercontent.com/96159292/151688767-be347c47-9278-4c48-83ef-02e736238515.png">


3. Risk analysis is performed using standard deviation (regular, annualized and moving) 
<img width="721" alt="Screen Shot 2022-01-29 at 10 09 04 PM" src="https://user-images.githubusercontent.com/96159292/151688797-00fdf478-64bb-41ea-aef2-65c6e7380435.png">
<img width="693" alt="Screen Shot 2022-01-29 at 10 09 17 PM" src="https://user-images.githubusercontent.com/96159292/151688798-4c421ded-dc8a-458b-a53d-93e4822c8df5.png">
<img width="753" alt="Screen Shot 2022-01-29 at 10 09 29 PM" src="https://user-images.githubusercontent.com/96159292/151688799-2084da37-08f1-4e48-80f7-30fbaf7036a5.png">


4. Risk/Return analysis is perfomed for each of the funds and the market, using Sharpe ratio

<img width="931" alt="Screen Shot 2022-01-29 at 10 10 33 PM" src="https://user-images.githubusercontent.com/96159292/151688828-61d4d7b5-5830-4192-8abc-3125a67bd955.png">


5. Beta of each of the funds is caluclated and analyzed to determoine the extent of portfolio diversification in eaach of the funds. 
 <img width="1080" alt="Screen Shot 2022-01-29 at 10 12 35 PM" src="https://user-images.githubusercontent.com/96159292/151688886-0c1f8b26-3bcf-4c9c-bb69-5ff5f433f6e2.png">

 <img width="790" alt="Screen Shot 2022-01-29 at 10 11 52 PM" src="https://user-images.githubusercontent.com/96159292/151688869-7a1e2a7d-8015-4f83-9879-4014d5e4e43c.png">



## Contributors
Brought to you by Ram Atmakuri (ram.atmakuri@outlook.com) 

## License [MIT] (https://choosealicense.com/licenses/mit/)
