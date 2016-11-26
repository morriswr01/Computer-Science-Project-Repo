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
    - Related to this is the problem that if a person tries to find a customers file there is a chance that they could pick up the wrong one. This is because each customer does not have any single unique identifier field that only one person can hold. It is unlikely that the wrong record would be chosen if multiple fields are used to search and verify a person(eg: name, date of birth) however it is still possible to have multiple of the same record with all the same data that are physically different customers.
    - Data redundancy is also possible if a customer leaves the bank for whatever reason and then re-joins and the bank does not ensure that the old one is removed or the problem stated above occurs and the wrong file is removed. Both ways can end up with repetition of data which can cause issues when keeping both files up to date.
    - The bank only holds one copy of each document and has no accessible backup meaning that if there is a fire or natural disaster and all of their records are destroyed customers can lose track of where their money is/should be held and the bank could go out of business very quickly.
    - Customers do not have quick access to their transaction history or current balance having to go into branch to request this information which can be a problem for people with a very tight schedule who just want to be able to access their banking information quickly through their smart phone or laptop that they may have on them at all time. This means customers can also go overdrawn unintentionally which can give them issues with credit score if a customer does not know he or she is overdrawn because they did not have easy access to their banking information.

+ Justify why it can be solved by a computer







+ Identify stakeholders
  - **The customers of the bank** will be the main stakeholders of this project as they are the individuals who will gain most from the production of an online system to replace the paper one. the customers needs from this program is that they must be able to access it anywhere with an internet connection so that they can view their details at a time flexible to them. Also it must replace the monthly paper statements if the customer so chooses if they feel that it is no longer needed due to this new online system. This will allow customers to manage their accounts more in real time rather than having to wait for the next opportunity to go out of their way to visit a branch making for a much more convenient and efficient banking experience. It will also provide a way of making transactions between different accounts or even to other customers of the bank which will be a very quick process again due to the lack of having to go into the bank to withdraw cash or write a check and send it to the target person.
  - **Employees of the banking company** will now have a much easier way to access and edit customer records with a new database that connects with the tables of the transaction database so that they both work together and are linked in such a way to avoid data redundancy and maintain data integrity. This will make the job of the bankers more efficient because it will provide a level of human error protection so that data is always kept up-to date in all places and that no data can be repeated. The database will provide a way of uniquely identifying each customer through a primary key or a secondary key which ideally will be more human readable so that a customer can be identified uniquely by their email for example. Their email will also be tied to this database so the bank can send emails about urgent issues with their account or the ability to send out messages about new account types that they are offering. The online database will also have the ability to be easily copied and backed up off site which increases the security and safety of the information that they are holding which in turn makes their bank much more attractive to new customers as they know their money and personal data is safe.

+ Research and justification of approach
  - While I am in the design and development of my banking application I will be taking inspiration from different examples of already developed/deployed banking systems and observing the features that stand out most to me. Namely I will be looking for the features that cater to the user through  asking questions like:
    - Does it look easy to use?
    - Are the navigational tools well designed and accessible?
    - Is there too much information on screen? Too many options to navigate?
    - Do different buttons have tool tips to display information about what the button does?
    - Is the account information displayed in a manner in which it is easy to identify separate accounts/ transactions?
    - Is it responsive? Does it respond to changes in screen size?(this is not measureable here)
+ Explain the features of the solution
+ Justify hardware and software requirements

## Design
