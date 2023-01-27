# BankSystem
Database for Bank Using SQL Server.

There are multiple banks and each bank has many branches. Each bank has a name, code, and address. Each branch has an address and a branch number.
Each branch has multiple customers. 
Each customer has SSN, name, phone, and address. Some customers may take different types of loans from these bank branches. 
Each branch offers multiple loans. Loan number, loan type, and loan amount must be kept for each loan.
One customer can have multiple accounts. For each account: the account number, balance, and type must be kept for it.

The bank system can include the following functionalities: 
1) Signing up a new user (customer, employee)
2) Updating user details.
3) Add bank (by admin).
4) Add bank branch (by Admin) 
5) Add a customer (by employee)
6) Showing a list of loans (industry loan, commercial loan, Personal loan)
7) Showing a list of customers
8) Showing a list of loans with customer name and employee name
9) Performing operations on loans: request and start operation (by customer)
10) Performing operations on loans: accept, reject, and pay the loan (by employee)

The SQL statement for each inquiry: 
a. What was the branch that has no customers?
b. What was the branch that has no employees?
e. Who was the employee with the maximum number of loans added? d. Who was the customer(s) who has a max number of loans?
e. Who was the customer(s) who didn't take any loans?
f. For each customer, retrieve all his/her information and the number of employees he deals with.
