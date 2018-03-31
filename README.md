# DesignPatterns
Design patterns are solutions to recurring problems; guidelines on how to tackle certain problems
I have included implementations of some design patterns in C# to help beginners like me get their feet wet.
There are better alternatives available for some of them in the .NET Framework, so this is by no means a comprehensive tutorial

Any comments and suggestions are welcome. If you want to add a new design pattern implementation, just follow the naming conversation, fork my repo and submit a pull request. Same goes for any improvements and modifications.

Based on the original [repo](https://github.com/abishekaditya/DesignPatterns), UIM diagrams would be added for each pattern.

## Types of Design Patterns
---------------------------
There are three kinds of Design Patterns

|Creational Patterns|Description|
|--|--|
|Absctract Factory|Provide an interface for creating families of relates or dependent objects without specifying their concrete classes|
|Builder|Separate the construction of a complex object from its representation|
|Factory Method|Creates an instance of several derived classes|
|Prototype|A fully initialized instance to be copied or cloned|
|Singleton|A class of which only a single instance can exist|

|Structural Patterns|Description|
|--|--|
|Adapter|Convert the interface of a class into another interface clients expect|
|Bridge|Separates an object's interface from its implementation|
|Composite|A tree structure of simple and composite objects|
|Decorator|Add responsibilities to objects dynamically|
|Facade|Provide a unified interface to a set of interfaces in a subsystem|
|Flyweight|A fine-grained instance used for efficient sharing|
|Proxy|Provide a surrogate or placeholder for another object to control access to it|

|Behavioral Patterns|Description|
|--|--|
|Chain of Resp.|A way of passing a request between a chain of objects|
|Command|Encapsulate a command request as an object|
|Interpreter|A way to include language elements in a program|
|Iterator|Sequentially access the elements of a collection|
|Mediator|Defines simplified communication between classes|
|Mememto|Capture and restore and object's internal state|
|Observer|A way of notifying change to a number of classes|
|State|Alter an object's behavior when its state changes|
|Strategy|Encapsulates an algorithm inside a class|
|Template Method|Defer the exact steps of an algorithm to a subclass|
|Visitor|Defined a new operation to a class without change|


## List of Design Pattern Implementations
-----------------------------------------

* [Adapter](/AdapterPattern)
* [Command](/CommandPattern)
* [Composite](/CompositePattern)
* [Decorator](/DecoratorPattern)
* [Facade](/FacadePattern)
* [Factory](/FactoryPattern)
* [Iterator](/IteratorPattern)
* [Observer](/ObserverPattern)
* [Singleton](/SingletonPattern)
* [State](/StatePattern)
* [Strategy](/StrategyPattern)
* [Template](/TemplatePattern)

## References
[Impressive introduction to Factory Pattern](http://ichennan.com/2016/08/09/DesignPattern.html)
[Singleton in Depth](http://csharpindepth.com/Articles/General/Singleton.aspx)
