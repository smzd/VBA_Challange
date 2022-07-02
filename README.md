                                                   #Overview of Project

VBA is a programming language that is used in Microsoft office applications. In the past, VBA used to be a dominant programming language on Wall Street to compute stock analysis. This is a great tool to get your hands dirty and familiarize yourself with programming language. We are helping Steve perform stock analysis in 2017 and 2018. By doing so, we can acquire skills in creating macros, using for loops, nested for loops, conditional logic, debugging, and refactoring codes.

                                                         #Analysis

In 2017 4 stocks out of 11 did outstanding, and only one stock had a negative return. If Steve had invested in DQ, he could have seen a 200% return in one year. Another great option was SEDG which had around 185% return.

![](https://github.com/smzd/VBA_Challange/blob/main/Resources/VBA_Challange_2017.png)

Fig: Stock Analysis 2017

In 2018 9 stocks did poorly, and two stores had over 80% return. If we compare the volume between 2017 to 2018, we see that in 2018 total volume for each index ticker increased significantly. This means there were many sellouts, hence all these negative returns.

![](https://github.com/smzd/VBA_Challange/blob/main/Resources/VBA_Challange_2018.png)

Fig: Stock Analysis 2018
 
Let's take a look closely, the ENPH index didn’t do as well as the DQ in 2017. But in 2018, it had another 80% positive return. We can conclude that ENPH is the winner in 2 years of investment.

                                                         #Results

Now Let's look at the runtime:

![](https://github.com/smzd/VBA_Challange/blob/main/Resources/VBA_Runtime.png)

Fig: Refactored Code Runtime 

Refactoring code helped us to lower our execution time. Our original code execution time was 0.29 seconds. When we refactored our code, it decreased to 0.08 seconds. Refactoring the stock analysis code made it faster.  

![](https://github.com/smzd/VBA_Challange/blob/main/Resources/Green_Stocks_Runtime.png)

Fig: Original Code Runtime

                                                         #Summary
                                                                 
Refactoring code: Refactoring code has both pros and cons.

Pros: Refactoring code can improve the code performance and have less computing time. It makes the code more organized and neat while keeping the same functionality. 

Cons: while refactoring the code can make it more organized, it is not improving the program's functionality. It can contribute to spending unnecessary time refactoring. Also, doing so can introduce more bugs in the program.

Our original VBA code has nested loops and multiple subroutines, making our executing time 0.29 seconds. We got rid of the nested loops and subroutines and introduced four arrays to store our values, which made processing the data faster, and the run time decreased to 0.08 seconds. When Steve has a larger dataset, it will run more quickly than the original program. 

We needed a good understanding of the core of our stock analysis program to refactor the code. Also, we had to test all the key points to ensure we didn’t encounter errors, which can be time-consuming. Refactoring the code didn’t change the functionality of the code. So, is it worth spending ample time refactoring the script to save a few milliseconds? 

