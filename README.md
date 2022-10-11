# **A.P.I.E**
## MidTerm assessment for Cohort12

- To demonstrate understanding of the fundamentals of O.O.P Abstraction, Inheritance, Encapsulation and Polymorphism
 

![FinalC12MidTermAss drawio](https://user-images.githubusercontent.com/10773482/195135748-b4af582f-2829-4cc4-9421-7c959e59a6e2.png)


### Push your code to github and DM repo to me before 2pm. Keep repo private until assessment is over!


#### Declaration, Instantiation and Initialization
> Use the UML above to answer the questions below in main()
- Create an instance of the Admin class (Not sure what that means? click link) - https://docs.oracle.com/javase/tutorial/java/javaOO/objectcreation.html
- Similarly, create 3 customer objects with the parameterized constructor and name them customer1, customer2, customer3 
*(Note that each customer has addresses and products) To save time, just use the same addresses and products for each customer

#### Invoking Methods on objects 
- Set customer1's accountBalance to negative number (- 150.0) without modifying the constructor. Then **get and print the balance right after doing so**. Oops!
- We do not want to be able to give a customer a negative balance. Therefore, go and modify your setter to ensure that we cannot give a customer a negative balance. *The account balance should not change if done the right way therefore test it out to make sure it works by getting and printing the balance*
- Without modifying the constructor or creating a new one. **Call a method** to give or award customer1 1000 reward points
- Invoke the method to make customer1 use 100 out of his/her 1000 reward points
- Call a method to get/retrieve ONLY the secondary address of customer1 and then print it out
- Once again without modifying the constructor. Set customer1's size to a Medium
- Invoke the print() method on the customer1 object to print out customer1's information

#### Invoking Methods on a Class and on objects again
- Consume all the products that are considered consumable according to the UML
- Set the amount of stamps to 3 (amount property/attribute of the postalStamp object) 
- Print all printable **objects** by leveraging one of your method methods.
- Get and print out the Total Price Of customer1's Products
- Sort and print out all products by price in reverse order 
- get and print out the List Of Product Prices Greater Than The Price Of Product Given
- **Invoke the static method named** addASingleProductToDirectoryTiedToCustomerByNameThenPrint **on customer1**.
- Right after that that do it again but the second time around invoke it on customer2 
- Then a third time but this time we want to call it on the customer3 reference variable.
> Your method works ONLY if customer1's info prints out as seen in the expected output.
>  This method should only print out the first customer' info that was added. 
>  Additional calls and attempts to add another entry to the map should not make a difference because the map is no longer empty. Therefore only the first entry should print out !!!
- Phew...finally have the admin reset customer1's password to **ReadyForBlock2**
- Get and print out customer1's password


# Expected Outputs
```
===Get and print out customer1's balance====
100.0
===useRewardPoints===
You Just used 10 points and now you have 90 points left
===getSecondaryAddressOfCustomer of customer1===
12 Real News Lane, Dover, DE 19901
===Print customer1's info with the print() method===
username: c1
reward points: 90
accountBalance: 100.0
Size: M
===Consume all consumable according to the UML===
Now consuming AA battery
Now consuming Vanilla ice-cream
===Print all printable objects===
name: Team-USA
amount: 3
price: 20.0
size: S
==============================
username: c1
reward points: 90
accountBalance: 100.0
Size: M
==============================
username: c2
reward points: 0
accountBalance: 500.0
Size: null
==============================
username: c3
reward points: 0
accountBalance: 250.0
Size: null
==============================
Admin's name is : Peter
==============================
===getTotalPriceOfCustomerProducts===
36.0
===reverseSortAndPrintAllProductsByPrice===
20.0
11.0
5.0
===getListOfProductsGreaterThanThePriceOfProductGiven===
[20.0, 11.0]
===addASingleProductToDirectoryTiedToCustomerByNameThenPrint===
c1 : Product{name='Vanilla', price=5.0, size=X}
ReadyForBlock2
```
### Push your code to github and DM repo to me before 2pm. Keep repo private until assessment is over!
