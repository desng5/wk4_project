# Week4_project
ROI calculator - OOP

This project I created a Rental Property calulator that allows different users to calculate their 'Retunr On Investment' (ROI) for their different properties.
The user will follow the code logic / prompts to use the ROI Calculator for a specific property.

## The Code/Program has 2 classes
  - Class for Rental Property
    -  __init__ Initializes Attributes
    -  2 other methods (cash_flow & cash_on_cash): 
        - 1st method will calculate the the expenses - rental income to figure out how much is being spent on every month
        - 2nd method will calculate the ROI - after user input of down payment, closing, and if there were any rehab/misc costs.   
  
  - Class for Users
    - Represents the user and their property. 
    - __init__ will initialize a user and a dict to store each property
    - 3 methods(add & remove & roi):
        - User can add one or multiple properites and give each Unique ID's.
        - They can remove a property
        - ROI will take in the Unique ID and check if its in dictionary and then calls on the instance(cash_on_cash) details to calculate

### Features & How to use
- First program will prompt user for their Name. 
- Then it will enter a While loop.
- It will ask user to enter a number to select an option.
- After user input the program will perform the corresponding actions for each option
    - 1(Add) 2(Remove) 3(Calculate ROI) 4(Exit)   
