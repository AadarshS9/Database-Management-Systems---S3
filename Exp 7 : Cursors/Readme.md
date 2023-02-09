1.Write a program in PL/SQL to create an explicit cursor with for loop to display the details of an employee.
2.Create a table called person which contains first name, last name, person id. Create an explicit cursor with for loop to display the first name and last name of the person whose person id> 50.
3.Write a program in PL/SQL to create a cursor displays the name and salary of each employee in the EMPLOYEES table whose salary is less than that specified by a passed-in parameter value.
4.A bank has an ‘ACCMASTER’ table where it holds the current status of a client’s bank account. Another table called ‘ACCTRAN’ holds each transaction as it occurs at bank (ie, Deposits/withdrawals of clients). The ‘ACCTRAN’ table must hold a flag indicating whether the transaction was credit or debit. Write SQL procedure to update the ‘ACCMASTER’ table and sets the balance depending upon whether the account is debited or credited. The updation should be done only for those records that are not processed.
ACCMASTER     ACCTRAN
Accno(PK)     Accno(FK)
Name          TransactionDate
Balance       Deb_cred                Debit/Credit
              Amount
              Processed               Yes/No flag

