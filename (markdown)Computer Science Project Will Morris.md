# **Computer Science Programming Project Documentation 16/17**
By Will Morris
___

## Analysis
+ Describe the problem
   - **A bank has a base of customers** all of which have single or multiple, savings or general accounts that they use to store and manage their money. The data for all of these accounts and customers are currently stored in paper form, this is done via a paper form for each customer which contains their personal details such as name, age, email, DOB etc. These forms are stored in individual "folders" and are identified by their fore/surname which are stored in cabinets in a massive file room in alphabetical order. For example a cabinet would represent surnames with initials A-C.

   If a customer wants to open an account with the bank a form must be filled out stating the details of it, such as: the customers full name so that the new account is linked to an individual; the type of account(savings, investment ISA etc); date that it was opened etc. This is then stored ideally with the customers personal form so that it can always be identified. The customers personal form will also have a list or field for accounts so that it can be identified that he/she has x number of accounts and they are listed by the name that the customer gave that account when they opened it for example "Retirement Fund".

   An accounts balance is stored on a server database which can only be accessed by the bank and various credit card machines where a user might use a card to by something in which case the card uses the name and account number to access the banks database and request funds. At this point a transaction is logged if the transaction is successful. However the customer can only review their transaction at the end of the month when a paper statement is sent out for each account that the customer possesses showing the transactions for that month. The customer can also go into the nearest branch in person to request the same paper copy to be printed off to show an up-to date balance and transaction log.
   - **Problems with this system**
    - Firstly, the system for sending out a paper statement every month means that a lot of paper and ink is used in printing which for a bank with thousands of customers can amount to a large sum of money that could be negated by being replaced with an online system. This gets far worse when customers start to have multiple accounts.
    - All records of accounts and customers are stored in paper format which poses multiple problems. Say an account document is removed from the customers file to be changed, when they go an put the document back they have the account number and customers name to go by however there is no unique customer identification field which can be put on the account form to say that the account belongs to this person and this person only. Instead the employee has to index the account by surname only and then if there are multiple of that surname maybe they check each of those customer folders to see which customer holds an account with that number. This can all go wrong if the employee is feeling lazy or for some reason doesn't realize that there are multiple customers in that surname and they just put it in the first one they see. All of this leads to misplaced and eventually lost information if the issues aren't resolved quickly.
    - The bank only holds one copy of each document and has no accessible backup meaning that if there is a fire or natural disaster and all of their records are destroyed customers can lose track of where their money is/should be held and the bank could go out of business very quickly.
    - Customers do not have quick access to their transaction history or current balance having to go into branch to request this information which can be a problem for people with a very tight schedule who just want to be able to access their banking information quickly through their smart phone or laptop that they may have on them at all time. This means customers can also go overdrawn unintentionally which can give them issues with credit score if a customer does not know he or she is overdrawn because they did not have easy access to their banking information.

+ Justify why it can be solved by a computer







+ Identify stakeholders
+ Research and justification of approach
+ Explain the features of the solution
+ Justify hardware and software requirements

## Design
