# customer_banking #
This repository is used for the Module 3 challenge of the UNC Chapel Hill AI Bootcamp course. 

## Description ##
This repository contains a program that mimics a customer banking system that will allow the user to calculate and track interest earned on savings and CD accounts. By running this applicaiton, users will be able to enter their savings and CD account information, see the interest earned, and view the updated balances after a specified number of months.

### Files in this Repo: ###

* Account.py - contains the Account class with methods to set the balance and interest

* cd_account.py - houses the create_cd_account function that will create a CD account   instance, calculate the interest earned based on user input, update the account balance with earned interest, and return the updated balance and interest earned.
   
* savings_account.py - houses the create_savings_account function that will create a CD account instance, calculate the interest earned based on user input, update the account balance with earned interest, and return the updated balance and interest earned.

* customer_banking.py - this file is where the main function will reside and prompt the user to enter the savings and CD account details, call the corresponding functions to calculate the interest earned and update the balances, and display the results.