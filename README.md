# Abstract Bank System
This is my solution to the below problem statement. The project was written using Visual Studio 2019 .NET Core Console Project. 

## Problem Statement
A bank holds diffeerent types of accounts for its customers: deposit accounts, loan accounts and mortgage accounts. Customers can be individual or companies. All accounts have a customer, balance and interest rate (monthly based). Deposit accounts allow depositing and withdrawing of money. Loans and mortgage accounts allow only depositing. All accounts can calculate their deposit for a given period (in months). In the general case, it is calculated as follows: number_of_months * interest_rate. Loan accounts have no interest rate during the first 3 months if held by individuals and during the first 2 months if held by a company. Deposit accounts have no interest rate if their balance is positive and less than 1000. Mortgage accounts have 1/2 the interest rate during the first 12 months for companies and no interest rate for 6 months for individuals. Your task is to write an object-oriented model of the bank system. You must identify the class, interfaces, base classes and abstract actions and implement the interest calculation functionality. 