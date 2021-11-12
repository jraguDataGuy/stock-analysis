# An Analysis of Stock Performance based on Volume and Price
Module 2 - Rice University Data Bootcamp - VBA 
## Overview of Project
For this analysis, we are looking to review total Volume of stocks and draw conclusion of their viability in investment selection by review their return vs. volume. We previously did this exercise through guided objectives and slightly different code. We learned a process of refactoring code in order to test our original code's relative effeciency. This is a common practice in coding, as "there are many ways to skin a fish."

## Results
Ultimately, we receive data from the same 12 tickers for 2017 and 2018

*2017 Volume and Returns*

![Image of 2017 Returns](https://github.com/jraguDataGuy/stock-analysis/blob/main/Resources/2017%20Stock%20Performance.png)
- In 2017, there were signifcant returns, with DQ pacing at 199.4% return. SEDG managed a 184.5% return with volume of over 200 million

*2018 Volume and Returns*

![Image of 2018 Returns](https://github.com/jraguDataGuy/stock-analysis/blob/main/Resources/2018%20Stock%20Performance.png)
- 2018 was not as fruitful, as all but 2 tickers saw losses. ENPH and RUN were the 2 stocks with positive returns, coming in above 80%. 

# Summary
## Advantages of Refactoring Code
As we proceed in this class and learn new coding techniques, it is natural we will develop more efficient processes. Cleaner code is easier to present and explain, while potentially saving time and money for the end user. The cleaner the code process, the faster computing processes for the end user. Time is always money. Refactoring can also help in maintaining items long term, and move them to scale. A clean code process can be repeated to achieve different results, which creates consistency. 

## Advantages and Disadvantages of our Refactored Stock Analysis
### Speed Analysis
- Our original code ran at the following speed. It must be caveated that this code also was for organizing tickers only. This did not include the formatting process, as that was created in a different sub():

*Image of 2017 Data Analysis for Original Code*
![Image of 2017 Code](https://github.com/jraguDataGuy/stock-analysis/blob/main/Resources/2017%20-%20All%20Analysis%20Code.png)

*Image of 2018 Data Analysis for Original Code*
![Image of 2018 Code](https://github.com/jraguDataGuy/stock-analysis/blob/main/Resources/2018%20-%20All%20Analysis%20Code.png)

- After the refactoring process, our speeds increased even with the addition of formatting. We add several For Loops, where the original code had a long For Loop for all the tickers in the original array. We established a numeric "tickerIndex" to move through the collection of Volume, ending price, and starting price. The individual For Loops for processes made the coding process easier to follow, while quickening the individual processes.:

*Image of 2017 Data Analysis with Refactored Code*
![Image of 2017 Refactored](https://github.com/jraguDataGuy/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

*Image of 2018 Data Analysis with Refactored Code*
![Image of 2018 Refactored](https://github.com/jraguDataGuy/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)
