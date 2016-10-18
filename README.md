# Java-Interview-Question
Core Java Interview Question

1. Can you override final method in Java?
Ans: No, If a method cannot be inherited, then it cannot be overridden. A subclass within the same package as the instance's superclass can override any superclass method that is not declared private or final. A subclass in a different package can only override the non-final methods declared public or protected.

2. Why does Java not allow to override static method?
Ans: Overriding depends on having an instance of a class. The point of polymorphism is that you can subclass a class and the objects implementing those subclasses will have different behaviors for the same methods defined in the superclass (and overridden in the subclasses). A static method is not associated with any instance of a class so the concept is not applicable.

3. Can a final and static method be overloaded?
Ans: yes, overloading final and static method is possible in java. As final and static methods are restricted not to override the methods.

4. What is Oops?
Ans: Object Oriented Programming is a programming method that combines:
a) Data
b) Instructions for processing that data
into a self-sufficient ‘object’ that can be used within a program or in other programs.

5. What is Object in Java?
Ans: Object is budle of related variables and methods. Object has two characteristics: state and behaviour.

6. What is Class in Java?
Ans: Class is prototype that defines the variables and methods common to all objects of certain kind.Member Functions operate upon the member variables of the class. An Object is created when a class in instantiated.

7. What is constructor?
Ans:  A special member function which will be called automatically to initialize the data member of a class whenever object is instantiated.

8. What is abstraction in Java?
Ans: The purpose of abstraction is to hide information that is not relevant or rather show only relevant information and to simplify it by comparing it to something similar in the real world.

9. What is Encapsulation in Java?
Ans: Encapsulation means the localization of the information or knowledge within an object.way to bring in Encapsulation
1) Make the instance variables protected.
2) Create public accessor methods and use these methods from within the calling code.
3) Use the JavaBeans naming convention of getter and setter.
Eg: getPropertyName, setPropertyName.

10. What is Inheritence?
Ans: The process by which one class acquires the properties and functionalities of another class. Inheritance provides the idea of reusability of code and each sub class defines only those features that are unique to it.

Inheritance is a mechanism of defining a new class based on an existing class.
Inheritance enables reuse of code. Inheritance also provides scope for refinement of the existing class. Inheritance helps in specialization
The existing (or original) class is called the base class or super class or parent class. The new class which inherits from the base class is called the derived class or sub class or child class.
Inheritance implements the “Is-A” or “Kind Of/ Has-A” relationship.

11. What is Polymorphism?
Ans: Polymorphism is a feature that allows one interface to be used for a general class of actions. It’s an operation may exhibit different behavior in different instances. The behavior depends on the types of data used in the operation. It plays an important role in allowing objects having different internal structures to share the same external interface. Polymorphism is extensively used in implementing inheritance.

12. 

