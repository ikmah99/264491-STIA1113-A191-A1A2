# Student Info
Matric: 264491 
Name: Ahmad ikmah bin sujali

## Introduction
In this assignment, I learned to create a car loan calculator by writing a pseudocode, drawing a flow chart and writing a java code. I also learned the formula to calculate and apply in java program. Beside that, the car loan calculator used to calculate the monthly repayment of car, loan of car, principal of car, interest of car and balance payment of car.

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
# Screenshot of the Output
https://github.com/ikmah99/264491-STIA1113-A191-A1A2/blob/master/output.png
