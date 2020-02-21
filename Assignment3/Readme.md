## Links to the document:
https://docs.google.com/document/d/1sLjzkDYLQh5M-1VvAeyIWzT8TTbf9C0UY25CfDvETtw/edit?usp=sharing

### About the dataset:
The dataset talks about the different sales based on different marketing factors such as TV Marketing and Radio Marketing. It also has the data on adstock models which can help us to use it for getting different insights in the visualisation. 
The following is the description of the test dataset:

base_sales &rarr Sales without ad spending </br>
tv_Sales_1 ==>  Sales with TV spending + adstock model 1 </br>
temp ==> Temperature (normalized) </br>
tv_spend ==> Spending on TV ads </br>
week ==> Week number </br>
adstock_TV_1 ==> Adstock contribution for model 1 </br>
tv_Sales_2 ==> Sales with TV spending + adstock model 2 </br>
tv_Radio_Sales_1 ==> Sales with TV spending + Radio spending + adstock model 1 </br>
tv_Radio_Sales_2 ==> Sales with TV spending + Radio spending + adstock model 2 </br>
radioSpend ==> Spending on Radio ads</br>
tv_Sales_2_Adstock ==> Adstock contribution for model 2</br>
tv_Radio_Sales_1_Adstock ==> Adstock contribution for model 3</br>
tv_Radio_Sales_2_Adstock ==> Adstock contribution for model 4</br>



### Steps for the Assignment 3 part 1
1. Reading the file into the pandas dataframe
2. Calculating the value of sales done by the TV ads.
3. Took the average of the two tv sales with two different ad stocks and put the final value on the 
4. Similarly for the Radio TV as sales the average of the two different sales associated with two different ad stocks were taken.
5. Finally the dataframe was written to csv and downloaded into the local system.
### Steps for the Assignment 3 part 2
1. The csv was loaded in another notebook so that TV ad expenditure along with base sales vs TV ad sales can plotted in the same graph axes.
2. Similarly the other graph was plotted so that Radio ad expenditure could be seen with base base sales + Radio and TV as expenditure altogether.
