# Analysis of the Performance of Green Stocks in 2017 and 2018

### The analysis of the Green Stocks was completed in order to help determine a suitable investment in the Green Energy sector of the stock market. The original code was created with multiple loops and would not be efficient if trying to compare hundreds or thousands of different stock tickers. The purpose of refactoring the code was to make it more efficient by creating an index that would run through the tickers in one loop, thus making it run much faster. 

## Stock Analysis

#### When given the starting and ending prices for 12 different stock tickers for the years 2017 and 2018, the goal of the code was to pull out each individual stock ticker and list it, along with its total volume and return for each year. This information is very useful to determine a suitable investment moving forward. As you can see from the below, the performance of Green Energy stocks in 2017 was very good. If someone were to decide on an investment just using this information, they would feel that any of the stocks would be suitable, except for TERP.

![All_Stocks_2017](https://user-images.githubusercontent.com/81929616/116821442-e6e92980-ab47-11eb-95df-3b5ce8485c1e.png)

#### However, after running the same information for the year 2018, you can see that the returns differed drastically. The volatility shown in this area of the market is very high and requires research to be undertaken for multiple years before determining an appropriate investment. The only two stocks that had a positive return for both 2017 and 2018 were ENPH and RUN.

![All_Stocks_2018](https://user-images.githubusercontent.com/81929616/116821565-65de6200-ab48-11eb-93a0-fea46a1a563f.png)

#### In conclusion, there only seem to be two suitable stocks to invest in based on the yearly returns: ENPH and RUN. There are many risks involved, as seen with the drastic differences between returns in 2017 and 2018 with almost all of the stocks involved.

## Refactoring the Original Code

#### The second part of this project was to refactor the original code to make the analysis run more quickly. The origninal code was not efficient and provided longer wait times, even though there were only 12 stock tickers to run through.

![Original_Code_2017](https://user-images.githubusercontent.com/81929616/116821787-472c9b00-ab49-11eb-86d2-714266e43a35.png) ![Original_Code_2018](https://user-images.githubusercontent.com/81929616/116821793-4b58b880-ab49-11eb-961c-d463d083e918.png)

#### If there were hundreds or thousands of tickers to analyze, the wait time would be very lengthy without refactoring the code. By creating a ticker index and allowing it to run through the analysis in one loop, we were able to reduce the amount of time the code took to complete by almost 90%. This would ultimately be immensely important if the data was much larger and required a much more robust analysis. The screenshots of the timing show how much more efficient the refactored code is.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/81929616/116821978-64159e00-ab4a-11eb-8aca-ded23dbf85f3.png) ![VBA_Challenge_2018](https://user-images.githubusercontent.com/81929616/116821981-67a92500-ab4a-11eb-92e6-83d36830f340.png)

## Summary

#### When it comes to refactoring code in general, I feel there are far more advantages than disadvtanges.

1. Refactored code runs much faster than the code that is not refactored. If the analysis needs to be conducted on very large amounts of data, the time saved using this refactored code could be helpful.
2. Refactored code is broken down in a clearer manner for the developer and is more concise. If there is an issue with it, it will be easier to identify and fix.
3. If reviewing code with a colleague or teacher, they may be able to understand your code much easier when it is refactored.

#### The only real disadvantage I can see is that it is a time consuming process to refactor code. If you have a deadline to meet and the amount of time it will take to refactor the code is not available, the original code must be used.

#### Speaking directly about this project, the one major advantage that was seen was the time decrease in the running of the code. While the original code only took a little over 1 second to run, and this is by no means a deal breaker to complete the project, it could be an issue if we had to run this code using more data. The other advantage was making the code much easier to understand and more concise, which allowed me to fix problems much easier, being as though there was less code to examine. All in all, using the refactored code was much better than using the original code.

#### As with refactoring code in general, the only disadvantage I saw with my newly refactored code was the time it took to actually perform the refactoring. 
