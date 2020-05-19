## Easy Exercises that you can use to test your programming skills

With nothing much to write lets get to business :muscle:

### 1. Classes
-----
#### Exercise 1 / 2020-05-19
- Create a class called Invoice that a hardware store might use to represent an invoice for an item sold at the store. An Invoice should include four pieces of information as instance variables — a part number (type String), a part description (type String), a quantity of the item being purchased (type int) and a price per item (double). Your class should have a constructor that initializes the four instance variables. Provide a set and a get method for each instance variable. In addition, provide a method named getInvoiceAmount that calculates the invoice amount (i.e., multiplies the quantity by the price per item), then returns the amount as a double value. If the quantity is not positive, it should be set to 0. If the price per item is not positive, it should be set to 0.0. Write a test application named InvoiceTest that demonstrates class Invoice’s capabilities.


#### Exercise 2 / 2020-05-19
- Create a class called Employee that includes three pieces of information as instance variables—a first name (type String), a last name (type String) and a monthly salary (double). Your class should have a constructor that initializes the three instance variables. Provide a set and a get method for each instance variable. If the monthly salary is not positive, set it to 0.0. Write a test application named EmployeeTest that demonstrates class Employee’s capabilities. Create two Employee objects and display each object’s yearly salary. Then give each Employee a 10% raise and display each Employee’s yearly salary again. 

#### Exercise 3 / 2020-05-19
- Create a class called Date that includes three pieces of information as instance variables — a month (type int), a day (type int) and a year (type int). Your class should have a constructor that initializes the three instance variables and assumes that the values provided are correct. Provide a set and a get method for each instance variable. Provide a method displayDate that displays the month, day and year separated by forward slashes (/). Write a test application named DateTest that demonstrates class Date’s capabilities. 


#### Exercise 4 / 2020-05-19
- Define a class Human with properties "first name" and "last name". Define the class Student inheriting Human, which has the property "mark". Define the class Worker inheriting Human with the property "wage" and "hours worked". Implement a "calculate hourly wage" method, which calculates a worker’s hourly pay rate based on wage and hours worked. Write the corresponding constructors and encapsulate all data in properties.
