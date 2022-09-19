# Stock Analysis
## Comparing The differences Of Stock Performance Year over Year
We first wanted to take a look at the performance of a stock that our clients parents were interested in to determine whether it might be a good investment. The project grew in scope, both with the number of stocks, as well as the stocks performance year over year between 2017 and 2018. It became clear that some changes should be made to the code in order to process the data more efficiently and provide a more user friendly interface for the clients.

### Initial Results: A simple yet effective view of one stocks performance in 2018
Using the code here I combined the total traded volume, and calculated the overall peformance of the stock based on the initial value and the year end value.

### DQ Code
![DQ_Code](https://user-images.githubusercontent.com/110148559/190835792-3093273f-7bdb-4490-be23-153b81618e9c.png) 

### DQ Performance in 2018
This showed a significant loss, prompting the client to ask for a broader analysis.

![DAQO_Performance_2018](https://user-images.githubusercontent.com/110148559/190835620-258c8e7d-05b4-4a0e-9676-04ca3ab8c653.png)

Updating the code to include a broader scope of related stocks in 2018 was mostly straighforward, adding an array of tickers to the query and aggregating the data into a useful table that showed two stocks that performed well based on trade volume and growth.

![Ticker_Array](https://user-images.githubusercontent.com/110148559/190836092-a8256254-6020-4861-89fc-316c5d547cfc.png)

The output of this update is attached below, and based on that the client was interested in seeing the performance of the stocks year over year from 2017 to 2018.  

![VBA_Challenge_2018](https://user-images.githubusercontent.com/110148559/190836151-acd855ff-24d6-447a-b996-2f9fc09daa7f.png)

### Final Analysis
Updating the Code once again and simplifying the output parameters allowed me to display the same data, but in a more user friendly and interactive way. Being able to quickly see the performance of the stocks between 2017 and 2018 allowed the client to make more educated investment decisions. I also included a timer to see the performance upgrade in the code itself.

![All_Stocks_2017](https://user-images.githubusercontent.com/110148559/190836549-4f570874-86d6-4169-bb77-68d0266deb1f.png)
![VBA_Challenge_2018_Refactored](https://user-images.githubusercontent.com/110148559/190838281-a70980a7-de51-4824-826e-eaae1a78a9fc.png)

## In Summary: 
### There are advanatages to writing clean and adaptable code
Using code that is written with the ability to scale up or down makes sense. After the initial request and the first round of edits it was clear that a lot of time could have been saved had the code been more easily adaptable using variables instead of hard-coding. Poring over the code and changing it line by line opens the door to too many errors, and is very time consuming. Using variables allows large scale changes to be made to the scope of the analysis with relatively low probablilty for errors. 

Once the code was refactored and streamlined, the data output was much faster and could easily be applied to an even larger dataset. If the client was interested in looking outside of the initial scope of "green stocks" the code could easily be scaled up to include a more broad array of stock tickers and still perform the function quickly.
