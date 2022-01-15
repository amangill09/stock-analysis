# stock-analysis

## Overview of Project

In this project we are analysis stocks data, mainly volume and daily strike price for a particular year. We are being asked to present a summary that will help decide which green stocks are best for investment this year

## Results

In our analysis, we are using two factors to determine if a stock is worth investment. We are looking at the volumne of stocks being traded and the return in a calendar year. Following topics explore these findings:

### Volume of stocks
Volume is a good indicator to understand quantitative aspect of stock trades. It shows how many trades are being executed for a stock and gives an inverstor an idea about general interest in the stock. To better analyse this I added **a macro that sorts the tickers based on descending values of 'Total Daily Volume"**. This will give us an opportunity to review top volumnes easily. Here we see that, for year 2017, SPWR and FSLR are much ahead than rest of the stocks. For 2018, the list is dominated by ENPH, SPWR, RUN and FSLR

### Return
Another way to analyse stocks is to review the return. It shows the percentage change in stock price over an year. After adding **a macro that sorts returns**, we see that DQ, SEDG, ENPH and FSLR had top returns for year 2017. For 2018, the only two stocks that returned postive returns were RUN and ENPH.

## Summary
Combining the volume and return analyses, we can predict a stock that will be most beneficial in next year. The runner up is RUN (no pun intended). This stock had moderate gains in 2017 (5.5% retrun) but was really profitable in 2018 (84% return), while maintaning solid trading volume in both years (267M and 502M respectively). However, the best stock from this list is ENPH that had a volume of 221M and 607M and returns of 129.5% and 81.9% in years 2017 and 2018 respectively. This stock will be a good logical investment. 

The code for this analysis ran pretty quickly. Here are the run times for 2017 and 2018: 
![Run timer for 2017](Resources/VBA_Challenge_2017.png) 
![Run timer for 2018](Resources/VBA_Challenge_2018.png)