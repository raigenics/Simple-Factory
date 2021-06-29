# Simple Factory Design Pattern
All creational design pattern does the same thing, it takes care of object creation of objects, But the difference is, they differ on how they do it. 
Since they deal with creation of object, they all fall under creational design pattern 

Now, in general terms factory means something that creates something…and in terms of design pattern simple factory is a factory that “Creates objects for us without exposing the instantiation logic to the client..”

It means the client is not aware of how the classes are getting created, basically the factory takes care of it. So, in simple factory design pattern, we have a factory class which has a method that returns different types of object based on given input.

This is by far one of the most commonly used creational design patterns, Could be because it is very easy to understand and fits in one or the other use case for almost all applications.

People often gets confused between Simple factory vs factory method, and sometime event with abstract factory. If you are one of them, then I strongly recommend you to watch these videos sequencialy -

# Simple factory - https://youtu.be/PvQZqOIthKE
# Factory method - https://youtu.be/tdMOdeewTnc
# Abstract factory -  https://youtu.be/HcxhrAqEukc

## Problem that simple factory tries to solve -
- new key word everywhere in the application 
  leads to significant duplication of code and it makes your code very tightly coupled.

- Makes code polymorphic. It gives you a flexibility when it comes time to change the application i.e. you can create new implementations without changing the client. 

Just opposite to the problems, we have these advantage of Factory Pattern:

- Factory helps to keep all object creation in one place and avoid spreading new key word across codebase. Hence it encapsulates object creation.	

- The Factory pattern also helps in the scalability of the application as the client code only refers to the interface and we can add more products implementing the interface without making many changes in the client code. 

- Code becomes more maintainable as the object creation is centralized.

- Makes your code testable.

- Code adheres to SOLID principle, hence your code by default follows the good practices of object-oriented design.

# For detailed explanation visit - https://youtu.be/PvQZqOIthKE
