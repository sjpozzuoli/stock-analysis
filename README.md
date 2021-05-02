# Analysis of the Performance of Green Stocks in 2017 and 2018

### The analysis of the Green Stocks was completed in order to help determine a suitable investment in the Green Energy sector of the stock market. The original code was created with multiple loops and would not be efficient to run if trying to compare hundreds or thousands of different stock tickers. The purpose of refactoring the code was to make it more efficient by creating an index that would run through the tickers in one loop, thus making it run much faster. 

## Stock Analysis

#### When given the starting and ending prices for 12 different stock tickers for the years 2017 and 2018, the goal of the code was to pull out each individual stock ticker and list it, along with its total volume and return for each year. This information is very useful to determine a suitable investment moving forward. As you can see from the below, the performance of Green Energy stocks in 2017 was very good. If someone were to decide on an investment just using this information, they would feel that any of the stocks would be suitable, except for TERP.

![All_Stocks_2017](https://user-images.githubusercontent.com/81929616/116821442-e6e92980-ab47-11eb-95df-3b5ce8485c1e.png)

#### However, after running the same information for the year 2018, you can see that the returns differed drastically. The volatility shown in this area of the market is very high and requires research to be undertaken for multiple years before determining an appropriate investment. The only two stocks that had a positive return for both 2017 and 2018 were ENPH and RUN.

![All_Stocks_2018](https://user-images.githubusercontent.com/81929616/116821565-65de6200-ab48-11eb-93a0-fea46a1a563f.png)

#### In conclusion, there only seem to be two suitable stocks to invest in based on the yearly returns: ENPH and RUN. There are many risks involved, as seen with the drastic differences between returns in 2017 and 2018 with almost all of the stocks inolved.

## Refactoring the Original Code

#### The second part of this project was to refactor the original code to make the analysis run more quickly. The origninal code was not efficient and provided longer wait times, even though there were only 12 stock tickers to run through.

![Original_Code_2017](https://user-images.githubusercontent.com/81929616/116821787-472c9b00-ab49-11eb-86d2-714266e43a35.png) ![Original_Code_2018](https://user-images.githubusercontent.com/81929616/116821793-4b58b880-ab49-11eb-961c-d463d083e918.png)

