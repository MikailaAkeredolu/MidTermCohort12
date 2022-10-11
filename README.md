# **A.P.I.E**
## MidTerm assessment for Cohort12

- To demonstrate understanding of the fundamentals of O.O.P Abstraction, Inheritance, Encapsulation and Polymorphism

![midlab drawio](https://user-images.githubusercontent.com/10773482/195013111-dbd00834-6490-4e77-823a-a24d7370b577.png)

#### Make sure you Push your code to github and DM repo to me before 2pm else you get a zero. You MUST Keep repo private until assessment is over at 2pm

#### Declaration, Instantiation and Initialization
> Use the UML above to answer the questions below in main()
- Create an instance of the Admin class (Not sure what that means? clicl link) - https://docs.oracle.com/javase/tutorial/java/javaOO/objectcreation.html
- Similarly, create 3 customer objects with the parameterized constructor and name them customer1, customer2, customer3 
*(Note that each customer has addresses and products) To save time, just use the same addresses and products for each customer

#### Invoking Methods on objects 
- Set customer1's accountBalance to negative number (- 150.0) without modifying the constructor. Then get and print the balance right after doing so. Oops!
- We do not want to be able to give a customer a negative balance. Therefore, go and modify your setter to ensure that we cannot give a customer a negative balance. The account balance should not change if done the right way therefore test it out to make sure it works!
- Once again without modifying the constructor or creating a new one. **Call a method** to give or award customer1 1000 reward points
- Invoke the method to make customer1 use 100 out of his/her 1000 points
- Call a method to get/retrieve only the secondary address of customer1 and then print it out
- Once again without modifying the constructor. Set customer1's size to a Medium
- Invoke the print() method on the customer1 object to print out its info

#### Invoking Methods on a Class
- Consume all the consumable products
- Set the amount of stamps to 3 (amount property/attribute of the postalStamp object) 
- Print all printable products by levearging your one of your utitlity methods
- Get and print out the Total Price Of customer1's Products
- Sort and print out all products by price in reverse order 
- get and print out the List Of Products Greater Than The Price Of Product Given
- Invoke the static method named addASingleProductToDirectoryTiedToCustomerByNameThenPrint on customer 1 and right after that that do it again but the second time on customer2 then a third time but on customer3. Your method works if ONLY customer1 prints out. See expected output
- Have the admin reset customer1's password to **ReadyForBlock2**
- Get and print out customer1's password
