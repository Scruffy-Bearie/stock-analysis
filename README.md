# Multi-Year Analysis of Green Energy Stocks Using Original and Refactored Code

## Overview of Project

Using programming tools such as iterative loops and if/then statements, it’s possible to use computers as tools for sorting through and assisting with the analysis of large data sets.  The client for this project, a recent graduate of a financial program, has asked for a multi-year analysis of the performance of green energy stocks to guide management of their parent’s investment portfolio.  Wherein initial analysis identified some intriguing trends and investment opportunities, the programming tools employed for data sorting/management were reflective of the limited amount of data being analysed and resulted in a process which would not be ideal for larger data sets.  As such, further analysis was conducted to determine if refactoring of the code could be employed to produce a process which harvested the same data for analysis but which would be better suited for use with larger data sets. 

##Results

Analysis of the performance of green energy stocks from both 2017 and 2018 using both the original and refactored code is summarised in Figure 1 and Figure 2.

### (i) Green Energy Stocks 2017 vs. 2018
Comparison of Figure 1 and Figure 2 reveals that overall performance of green energy stocks change dramatically from 2017 to 2018.  Wherein all of the green energy stocks analysed, with the exception of TERP, delivered a positive return in 2017, in 2018, perhaps owing to a change in the political climate in the U.S., performance of green energy stocks, in general, was poor with only ENPH and RUN delivering positive returns.  

### (ii) Original Code vs. Refactored
The original coding for analysis (see Figure 3: Original Code for Data Extraction) employed an array to identify each stock ticker and was constructed in such a way that the computer had to loop through the data for all stock tickers in order to extract the data required for analysis of each individual stock.  

The refactored code (see Figure 4: Refactored Code for Data Extraction) involved establishing additional arrays for data output and a “nested for loop” meaning that the computer had to loop through the entire data set only once to extract the data for each individual ticker.  Comparison of Figure 1 and Figure 2 reveals that although the original and refactored code extracted the same information from the data set, the refactored code allowed the computer to perform the task approximately 10x faster.

## Analysis

### (i) Green Energy Stocks 2017 vs. 2018
Although both ENPH and RUN delivered positive returns in 2018, they were not the top performers in 2017 and the political climate in the U.S., and attitudes towards green energy, continued to be “erratic” through to late 2021.  That said, further analysis covering a greater time frame would be beneficial in determining whether or not ENPH and RUN represent the best investment opportunity as compared to other green energy stocks.

### (ii) Original Code vs. Refactored
As evidenced by the results, refactoring code can result in a substantial decrease in processing time by streamlining, or making more efficient, the computational process.  Unfortunately, refactoring invariably takes time, is likely to result in code that is more complex and may have unforeseen consequences if the section of code refactored is part of a larger program.  That said, if the original code was assembled quickly and produces accurate results within a reasonable time frame it may be difficult to justify to a client the additional expenses associated with the refactoring process.

Although refactoring of the code for the VBA_Challenge resulted in a 10 fold decrease in processing time, owing to the size of the data set the original code resulted in a processing time of approximately 1 second.  That said, as much as the refactored code might be useful for future projects involving larger data sets, it is difficult to justify the amount of time and energy associated with the refactoring process in the context of the current analysis.
 
