**Database is created for banking**
Database used:redis

 Banking application that will provide with real-time updates on bank account. 
With Redis database customer be able to keep a close eye on spending with money. 

This configuration information includes

• Customer details 

• Branch where the bank located

• Account for each customer
 
• Transactions are used by customers

>Entity types:
Customer,
branch,
Account,
Transdetail.

Keys used as:
Customer id as custid,
Dob is date of birth of customers,
For branch id as bid,
Branch citt as bcity,
Opbalance for customer datenof open with deposit balance,
Actype for account type and acstatus for account status,
Tnum for transaction number,transtype for cash or cheque,
Transmedium for withdrawal or deposit.

Attributes for each entity :

For Customer entity
     
      -Custid,Name,City,Occupation,Dob

For Branch entity 
     
      -Bid,bcity

For Account entity

      -Acnum,custid,bid,opbalance,atype, acstatus 

For Transdetails entity 

    - tnum,acnum,,transtype,transmedium
