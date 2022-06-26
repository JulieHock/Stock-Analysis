# Stock-Analysis

## Overview of Project


Steve would like to do a deeper dive into the analysis of stocks for his parents.  Since Steve is looking at multiple years, he needs a program that will allow him to look at all stocks during different years.  Steve is interested in the stock title, total volume and the return, so he can better guide his parents on their investment journey.

## Results

**The Code**

With the code that was given, we were assigned to edit (refactor) the code to work for the given data.  In order to get the new code, I had to create an index, create the three output arrays and make sure that for each loop, the ticker volume started at zero.  
![image part 1](Refactored_Code_Part_1.png)

Then I needed to make sure that the code was running through all the lines of the spreadsheet, for the given year, to pull the information: adding up the total daily volume, determining the starting and ending tickers to then calculate the percent of return.
![image part 2](Refactored_Code_Part_2.png)

Once all of this data was gathered, it needed to be placed on the "All Stocks Analysis" sheet, within the document.  To do this, I needed to tell the code to drop the data on that sheet by activating it. The code already had the formatting in place.  
![image part 3](Refactored_Code_Part_3.png)


**The Comparison**

In 2017, there was only one stock (TERP) that did not have a successful return.  
![2017](2017_

In 2018, only two stocks had a successful return; ENPH and RUN.  
