# Student Info
Matric: 264491 
Name: Ahmad ikmah bin sujali

## Introduction
In this assignment, I have learnt to create a car loan calculator including write a pseudocode, draw a flow chart and write a java code. I have learnt the formula to calculate and apply in java program. By using while loop, I can run my program successfully and efficiency. I also learn how to use int, double, for loop and so on. User just have to enter car price and down payment amount in Malaysian Ringgit; car loan period in Years and interest rate in Percentage. Some limitation for user is car price cannot less than RM30,000, down payment cannot be negative, loan period cannot less than 5 years and more than 9 years, interest rate cannot less than 3% and more than 7%.

# PSEUDO-CODE  
START  
   Output "Enter car price(RM)"  
	 Input car price  
	 Loop the input car price if the user enter car price less than RM 30000  
	 Output "Enter down payment(RM)"  
	 Input down payment  
	 Loop the input down payment if the user enter the down payment less than RM 0  
	 Output "Enter loan period(year)"  
	 Input loan period  
	 Loop the input loan period if the user enter the loan period less than 5 years or more than 9 years  
	 Output "Enter interest rate(%)"  
	 Input interest rate  
	 Loop the input interest rate if the user enter the interest rate less than 3 or more than 7  
	 Calculate monthly repayment(RM)=((carprice-downpayment)* interestrate/100/12)+(carprice-downpayment)/(loanperiod* 12)  
	 Output monthly repayment  
	 Calculate Years= n th year  
   Calculate Principal= monthly repayment* 12* n th year  
   Calculate Interest= (car price-down payment)* interest rate/100* n th year  
   Calculate Balance= (monthly repayment* 12)* (loanperiod-n th year)  
	 Output years,principal,interest,balance  
   Loop years,principal,interest,balance depend on the loan period entered by the user  
END 

## Flow chart to print temparature

![Flowchart](https://github.com/zhamri/123456-STIA1113-A191-A1A2/blob/master/flowchart-example.png)

# Screenshot of the Output
https://raw.githubusercontent.com/ikmah99/264491-STIA1113-A191-A1A2/master/output.png
