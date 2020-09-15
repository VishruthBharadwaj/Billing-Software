# Billing System in Python (Electronic Store) (cw3-1)
## (Full Documentation)
It is tied in with composing a program in python of an electronic store that offers electronic machines like phone, laptop and HDD etc.



## Features of the project
The features of this program as follows;
1. To build a program which work in loop statement and show accessible items which are stored in text file. The program should wait for user to enter purchase details of interest. Program should not close or stop until and unless the user chooses to do as such.
2. Program had user interacts features which is request every question with customer and react that answer provide by customer.
3. Program had exception handling feature which is used when unexpected entered from user. Like, program expect to the integer value from customer but customer entered a string value then program request for integer value.
4.Interconnect the different module in main module for easy to run the full program. Like, read, write, and purchase module are connect with main module.
5. Program can read text file and overwrite or write new text file. In this program, I used products.txt file for store a data and read and overwrite on it.
6. Similarly, program create a unique invoice in text file format and its naming from current device date and time.

## Stepwise algorithm
- Step 1:	 Start 
- Step 2:	 products.txt file from given folder.
- Step 3: 	txt file is displayed in the screen with products available.
- Step 4:	Inputs customers name.
- Step 5: 	Inputs products name.
- Step 6:   Give details of Selected product
- Step 6: 	If product name is correct then go to next step or else remain in same step until valid name is provided.
- Step 7: 	Input quantity of the product.
- Step 8: 	If the input number of quantity is available then go to next step or else display Sorry!! a_name !, product is out of stock.
We will add stock of product later. 
Lets hope, you will get this product after next shopping
- Step 9: 	Ask customer do you want buy more products?(Y/N) If they select Y, go back to step 6, If they select no, then it won’t go to any steps.
- Step10: 	Price of the product with total amount is displayed.
- Step 11: 	If Total amount is greater than 10000rupees give discount of 500 rupees
- Step 12: 	Total price after the discount is calculated and display updated amount.
- Step 13:	Invoice is printed with customer name, date and time purchase. Products details, Grand total and at last Thank You customer for your shopping. See you again!
- Step 14: 	If more customers are there to purchase item ‘Y’ should be clicked and go to step or else end.
- Step 15:	 End.




## Testing
Testing is the technique where we check our program for program gives the expected output or not as well as the program has any error or bugs or not.
We can test how many products are there in store by typing python test.py in cmd 

## Steps to run the file
-->Just download the folder and run python main.py
-->To test the store products run python test.py