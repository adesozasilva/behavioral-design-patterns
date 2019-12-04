# Behavioral Design Patterns for Java

This repository will be introduced the structural GOF design patterns for Java. The patterns are:

1. Chain of Responsibility - Create a chain, where each object decides whether to process or transmit to another element of the chain.  **Usage examples:** When you need to execute different requests differently, whereas such possibilities are not known in advance.
2. Command - Allows you to create commands to queued for transaction flow control and enable rollback. **Usage examples:** When you need this object to be used to encapsulate all the information necessary to perform the action or trigger the event.
3. Iterator - This pattern is used to get a way to access the elements of a collection object in sequential manner without any need to know its underlying representation. **Usage examples:** When you have to go through a collection of objects without knowing their data structure.
4. Mediator is a design pattern that reduces coupling between components of program by making them communicate indirectly, through a special mediator object. **Usage examples:** When you need to control the intent among two or more objects, reducing the coupling.
5. Memento - Allows you to save and restore the state from an object without to reveal details of the implementation. **Usage examples:** When you need to restore old versions from an object.
6. Observer - Allows one objects to notify other objects about changes in their state. **Usage examples** when there is one-to-many relationship between objects such as if one object is modified, its depenedent objects are to be notified automatically.
7. Visitor - is a design pattern that lets you separate algorithms from the objects on which they operate. **Usage examples** When you need to change or execute an algorithm to a class.
8. Strategy - is a design pattern that lets you define a family of algorithms, put each of them into a separate class and make their objects interchangeable. **Usage examples*** use the strategy pattern when you want to use differents variants of an algorithm within an object and be able to switch from  one algorithm to another during runtime.