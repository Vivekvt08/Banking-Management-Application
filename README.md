# Banking-Management-Application
FullStack Baking Application with Spring Boot and Angular
This is a fullstack banking app developed using Java, Spring Boot, MySQL, and Angular

This application mimics the dashboard for bank employees. In this application, bank employee can

Register the new customer
Create the new bank account
Delete the existing account
View the list of all customers
View the list of all accounts
Transfer the fund between different accounts
Deposit the fund in the account
Withdraw the fund from the account
View the account statement of specific account
Backend APIs
Register Customer (POST): localhost:8080/customers
Create Account (POST): localhost:8080/accounts
Delete Account (DELETE) using account number: localhost:8080/accounts/{accountNumber}
View Customer List (GET): localhost:8080/customers
View Account List (GET): localhost:8080/accounts
Transfer Fund from one account to another (POST): localhost:8080/transactions/transfer
Deposit Fund in the account (POST): localhost:8080/transactions/deposit
Withdraw Fund from the account (POST): localhost:8080/transactions/withdraw
View Account Statement using account number (GET): localhost:8080/accounts/{accountNumber}
