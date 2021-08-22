# stocks-analysis

## Overview of Project
This project started was initiated to analyze the DAQO stocks for XXX' parents. 
However after the initial analysis we analyzed all the stocks since the DAQO stocks did not give promising results.
Hence stocks from the year 2017 and 2018 are being analyzed in the most optimal manner. 

### Results

#### Stocks Analysis
After analyzing the data for 2017 we found that all stocks except for ticker "TERP" gave us promising results. 
Ticker 'DQ' followed by 'SEDG' and 'ENPH' occupied the top 3 results. 

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/VBA_Challenge_2017.png)

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/volume2017.png)

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/returns2017.png)

However the same stocks gave up on giving returns in the year 2018. Infact only two stocks ENPH and RUN gave returns over 80% while the rest tanked to almost negative 50%.

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/VBA_Challenge_2018.png)

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/volume2018.png)

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/returns2018.png)

As per the current scenario, it would be recommended to invest in ENPH and RUN. TERP would never be a good choice since the returns came down to -7.2% in 2017 and -5% in 2018.

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/returns2018_Combo.png)


#### Code Analysis

Given the two codes the major comparison is with the for loops and how its executed. 
- In the first case where define the ticker variable first and then loop over from 0 to 11 to calculate the volume, startingprice and endingprice, in the refractored code we directly pass on the tickerIndex value to the tickerVolumes, tickerStartingprices and tickerEndingprices 
- In the first code we itereate based on the String (DQ and so on) which makes it a slower execution while in the second script we compare using numerical values to iterate the calculations

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/exectiming.png)

![](https://github.com/c3crocks/stocks-analysis/blob/main/Resources/refratorreddcomparison.png)


## Summary

- What are the advantages or disadvantages of refactoring code?
	- Advantages:
		- 
	- Disadvantages:
		- 
- How do these pros and cons apply to refactoring the original VBA script?
	- 


![](https://github.com/c3crocks/kickstarter-analysis1/blob/main/Additional_Images/GoalsPie.png)