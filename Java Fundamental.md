# Interview Questions for Java developer



1. ## final?

- A **modifier** that makes classes / attributes / methods **unchangeable** and **read-only**.



2. ## Primitive Data Type vs Non-Primitive Data Type

- Primitive : Shows the size or type of data. Already **pre-defined**.
  - Example : *byte, short, int, long, float, double, boolean, char*
- Non-primitive : **reference types**. They refer to objects. Defined by the programmers.
  - Example : *Class, Array, String*



3. ## double vs float?

- double : 15 digits after the decimal point.
- float : only 6 digits after the decimal point.
- **double is much safer** than float for most calculations



4. ## Widening Casting & Narrow Casting

- Casting : Happens when you assign a value of one primitive data type to another type.
- Widening Casting : Larger type to Smaller type. Automatically its done.
- Narrow Casting : Smaller type to Larger type. **Parentheses in front to the value**.



5. ## Short Hand If...Else (Ternary Operator)

   Syntax : *variable **=** (condition) **?** expressionTrue **:**  expressionFalse;*



6. ## Methods?

- A block of code
- Perform certain **actions** - also called **functions**
- To reuse code
- Only created within a class



7. ## Method Overloading

- Multiple methods can have the **same name** with **different parameters / return** types.



8. ## OOP?

- Object Oriented Programming
- About creating **objects** that includes data / methods.
- Advantage : 
	1. **Reuse the code** so that we can have less code and shorter development time - code efficiency up!
	2. **Clear structure**.



9. ## Class vs Object?

- Ex) Class - Fruit 	/ 	Objects -  Apple, Banana, Mango.
- Class : **a template of objects**.
- Object : **an instance of a class**.



10. ## Static vs Public(Non-static)

- Static method : it can be accessed **WITHOUT creating an object of the class.**
- Public method : it can be only accessed BY objects.
- *Details : [https://www.w3schools.com/java/java_class_methods.asp](https://www.w3schools.com/java/java_class_methods.asp)*



11. ## Constructor?

- Used to **initialize** **objects** and set initial values for object attributes.



12. ## this?

- The keyword used to **refer to the current object**.



13. ## Encapsulation? *(Security)*

- Used to make sure that the "sensitive" data is hidden from users.
- Increases security data.

1. Declare attributes as **private**
2. Provide "**get**" and "**set**" methods to **access the private attributes** we just declared in (1).



14. ## Inheritance? *(Re-usability)* 

- subclass (*child class*)
- superclass (*parent class*)
- Keyword, "**extends**", is used to inherit from a class
- Able to **re-use attributes and methods** of an existing class when you create a new class.



15. ## Polymorphism? *(Re-usability)*

- Same idea as Inheritance.
- Can **re-use attributes and methods**.
- When we want to use the inherited methods to **perform different tasks**, then we can apply Polymorphism.
- This allows us to take **a single action in different ways**.



16. ## Abstraction? *(Security)*

- Hide certain details and only show the important details of an object.
- A restricted class that does not allow to create objects.
- If we want to access the abstract class, it **must be inherited** from another class.
- **Abstract method** : does **NOT** have a body.



17. ## HashMap?

- Store items in **Key/Value pairs**.
- Key : index

