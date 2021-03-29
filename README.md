# Stock-Analysis

## Overview
  
  Steve's parents are interested in investing in Green Energy, and are currently invested in DAQO Green Energy. Steve has assembled an excel file of other green energy stocks, as well as DAQO, for 2017 and 2018. Steve's parent's believe the more actively stock is traded, the more likely it is to accurately reflect the value of the stock. Therefore, we have analyzed the stock tickers by both determining their percent return (the ratio of the price of stock at the end of the year to the price of stock at the beginning of the year quantity minus one) and their annual volume. Stocks with both the greatest volume and the greatest return, would be the best investment opportunity for Steve's parents. 

## Results

  <img width="1417" alt="Original (2017)" src="https://user-images.githubusercontent.com/80495710/112835035-bd2f7500-9066-11eb-9e44-7e7e333ea6cd.png">

<img width="1398" alt="Screen Shot 2021-03-29 at 8 22 01 AM" src="https://user-images.githubusercontent.com/80495710/112835902-e3a1e000-9067-11eb-9c8c-03f3e6aea312.png">


For 2017, DQ (the ticker for DAQO Green Energy) had the *highest* overall percentage return, but had the *lowest* total volume for the year. In 2018, DAQO's volume *rose to nearly triple* the previous year's volume, but had the *lowest* percent return. So one year, DAQO didn't have enough volume of trading to be truly accurate, but had extremely high return. The next, it had enough volume, but the return was extremely low. 

I would encourage Steve's parents to invest in ENPH. For 2017, their return was +129.5% (the 3rd highest that year) with a total volume of 221,772,100 (in the top half), and for 2018, their return was +81.9% (one of only two positive returns) with a total volume of 607,473,500 (the highest that year). Of course, more years would need to be added in order to establish a trend, but the stock for this company seems to be the best for maintaining positive return with high volume. 

<img width="497" alt="Screen Shot 2021-03-29 at 8 40 16 AM" src="https://user-images.githubusercontent.com/80495710/112837873-69bf2600-906a-11eb-82a1-c8481b8d7de6.png">

Originally, the data was analyzed using two separate for loops. The first went through the list of tickers, while the second went through the rows to gather information about the specified ticker. The problem with this method (the reason it was slow) is that the second loop has to look at every row in the data sheet before moving on to the next ticker. So it looks at more that 2500 rows that it doesn't need to before going to the next ticker. 
  
## Summary

  1. Whataretheadvantagesordisadvantagesofrefactoringcode?
  2. HowdotheseprosandconsapplytorefactoringtheoriginalVBA script?

