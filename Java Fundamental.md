# Interview Questions for Java developer

<br/>

1. ## final?

- A **modifier** that makes classes / attributes / methods **unchangeable** and **read-only**.

<br/>
<br/>

2. ## Primitive Data Type vs Non-Primitive Data Type

- Primitive : Shows the size or type of data. Already **pre-defined**.
  - Example : *byte, short, int, long, float, double, boolean, char*
- Non-primitive : **reference types**. They refer to objects. Defined by the programmers.
  - Example : *Class, Array, String*

<br/>
<br/>

3. ## double vs float?

- double : 15 digits after the decimal point.
- float : only 6 digits after the decimal point.
- **double is much safer** than float for most calculations

<br/>
<br/>

4. ## Widening Casting & Narrow Casting

- Casting : Happens when you assign a value of one primitive data type to another type.
- Widening Casting : Larger type to Smaller type. Automatically its done.
- Narrow Casting : Smaller type to Larger type. **Parentheses in front to the value**.

<br/>
<br/>

5. ## Short Hand If...Else (Ternary Operator)

   Syntax : *variable **=** (condition) **?** expressionTrue **:**  expressionFalse;*

<br/>
<br/>

6. ## Methods?

- A block of code
- Perform certain **actions** - also called **functions**
- To reuse code
- Only created within a class

<br/>
<br/>

7. ## Method Overloading

- Multiple methods can have the **same name** with **different parameters / return** types.
### Example

```java
int myMethod(int x)
float myMethod(float x)
double myMethod(double x, double y)
```

<br/>
<br/>

8. ## OOP?

- Object Oriented Programming
- About creating **objects** that includes data / methods.
- Advantage : 
	1. **Reuse the code** so that we can have less code and shorter development time - code efficiency up!
	2. **Clear structure**.

<br/>
<br/>

9. ## Class vs Object?

- Ex) Class - Fruit 	/ 	Objects -  Apple, Banana, Mango.
- Class : **a template of objects**.
- Object : **an instance of a class**.

<br/>
<br/>

10. ## Static vs Public(Non-static)

- Static method : it can be accessed **WITHOUT creating an object of the class.**
- Public method : it can be only accessed BY objects.
- *Details : [https://www.w3schools.com/java/java_class_methods.asp](https://www.w3schools.com/java/java_class_methods.asp)*

<br/>
<br/>

11. ## Constructor?

- Used to **initialize** **objects** and set initial values for object attributes.
- The constructor name must **match the class name**, and it cannot have a **return type**.

<br/>
<br/>

12. ## this?

- The keyword used to **refer to the current object**.

<br/>
<br/>

13. ## Access Modifier?

- The **access level** for classes, attributes, methods and constructors.
- public : Accessible for all classes.
- private : Only accessible within the **declared class**.
- protected : Accessible in the **same package** and **subclasses**.

<br/>
<br/>

14. ## Encapsulation? *(Security)*

- Used to make sure that the "sensitive" data is hidden from users.
- Increases security data.

1. Declare attributes as **private**
2. Provide "**get**" and "**set**" methods to **access the private attributes** we just declared in (1).

#### Why Encapsulation?
- Better control of class attributes and methods
- Class attributes can be made **read-only** (if you only use the `get` method), or **write-only** (if you only use the `set` method)

<br/>
<br/>

15. ## Inheritance? *(Re-usability)* 

- subclass (*child class*)
- superclass (*parent class*)
- Keyword, "**extends**", is used to inherit from a class
- Able to **re-use attributes and methods** of an existing class when you create a new class.

<br/>
<br/>

16. ## Polymorphism? *(Re-usability)*

- Same idea as Inheritance.
- Can **re-use attributes and methods**.
- When we want to use the inherited methods to **perform different tasks**, then we can apply Polymorphism.
- This allows us to take **a single action in different ways**.

<br/>
<br/>

17. ## Abstraction? *(Security)*

- Hide certain details and only show the important details of an object.
- A restricted class that does not allow to create objects.
- If we want to access the abstract class, it **must be inherited** from another class.
- **Abstract method** : does **NOT** have a body.

<br/>
<br/>

18. ## HashMap?

- Store items in **Key/Value pairs**.
- Key : index

<br/>
<br/>

19. ## MVC?

- Consisting of three components - **Model**, **View**,  and **Controller**
- Model : **Store** data and queries.
- View : Visual component that is responsible for **UI**.
- Controller : **Connector** between Model and View.
  - Receive input --> Interpret it --> There is anything to change, update it to View and Model

<br/>
<br/>

20. ## Scanner?

- A class used to get **user input**.

  1. Create a Scanner object - *Scanner myInput = new Scanner(System.in);*

  2. Read user input - *String userName = myInput.nextLine();*

<br/>
<br/>

21. ## ArrayList vs Built-in array?

- ArrayList : A **resizable** array.
- Built-in array : The size of an array can **NOT** be modified.
- Methods : add(), remove(), clear(), get(), set(), size()

<br/>
<br/>

22. ## ArrayList vs LinkedList?

- ArrayList : When a new element is added, it is placed to **the end of the array**. If the array size is not bit enough, **the new element replaces the old one at the end.**
- LinkedList : It is best use a LinkedList when you need to add / remove items from **the beginning, middle or end of the list**. It does **not remove the old element** but it creates a new container and put the new element and link containers.
- *Details : [https://www.w3schools.com/java/java_linkedlist.asp](https://www.w3schools.com/java/java_linkedlist.asp)*

<br/>
<br/>

23. ## Methods in ArrayList, LinkedList, and HashMap

- ArrayList : add(), remove(), clear(), get(), set(), size() ...
- LinkedList : addFirst(), addLast(), removeFirst(), removeLast(), getFirst(), getLast() ...
- HashMap : put(), get(), remove(), clear(), size(), keySet(), values()

<br/>
<br/>

24. ## HashSet?

- A collection of items where every item is **unique**.
- Methods : add(), **contains()**, remove(), clear(), size()

