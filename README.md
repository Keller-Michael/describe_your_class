# 🖥️ Tell about your new awesome class

*Yes, each of us has experienced this: It's a cool party, everyone is having fun and you want to tell your friends about this new, super awesome class you wrote last weekend during a long night shift. But then you simply don't have the words to describe so much technical beauty. Ouch! But wait, this doesn't have to happen to you again. Here are a few ideas for describing your class to others.*

Ok, the section before was the fun side of this repository. Here comes the hard truth: We developers rarely talk about our super-cool classes at parties, but we talk more often at work with colleagues, e.g. during a code review. This is exactly what the approaches from this repository are intended to help with. 

Good luck and have fun! 😃

## Table of content

* [Describe the high-level context of your class](describe-the-high-level-context-of-your-class)
* [Describe your class based on its characteristics](describe-your-class-based-on-its-characteristics)

## Describe the high-level context of your class

This is a simple, high-level classification of your class into two categories:

* **Business object**: Your class represents a business object or part of it. An example of a business object is a purchase order; part of a purchase order are its purchase order items. 

* **Technical object**: Your class represents a technical object such as an email or a service for sending an email.

## Describe the character of your class

| Characteristic | Description |
| :--- | :--- |
| Utility class | Your class is entirely static. |
| Test class | Your class contains test methods or is part of a test infrastructure. |
| 

## Describe the tier your class belongs to

Your class belongs to one of these tiers:

* Presentation tier
* Application tier
* Data tier

Check this [Wikipedia article](https://en.wikipedia.org/wiki/Multitier_architecture#Three-tier_architecture) for more information.

## Describe the layer your class belongs to

Your class belongs to one of these layers:

* Presentation layer 
* Application layer 
* Business layer 
* Data access layer

Check this [Wikipedia article](https://en.wikipedia.org/wiki/Multitier_architecture#Layers) for more informationen.

## Describe the focus of your class

* Focus on data
* Focus on algorithms
* Good mix of both

## Describe your class based on its characteristics

| Characteristic | Description |
| :--- | :--- |
| is local (possibly ABAP-specific) | Your class is in another development object such as a report. | 
| is global (possibly ABAP-specific) | Your class is part of the repository. |
| is stateful | The class has attributes. |
| is stateless | The class has no attributes. |
| is mutable | The attributes of the class can be changed. Typically there are Setter-methods for this task. |
| is immutable | The attributes of the class cannot be changed and are initially set once in the constructor. |
| is abstract | Your class models some common behaviour for one or more subclasses. |
| is final | No subclass of your class is possible. |
| is completely static | Your class offers only static methods and attributes. |
| inherits from | Bring your class in context of the class it's inherits from. |
| is testable | You provide unit tests for your class. |
| implements interface(s) | Your class makes use of one or more interfaces. | 
| has factory methods | Describe why the standard constructor was not enough. |
| has public attributes | Why are the attributes public and not private with Getter/Setter-methods? |

## Describe your class based on its neighborhood

Your class works with other classes to implement functionality. This can be done via [inheritance](https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming)) or [composition](https://en.wikipedia.org/wiki/Object_composition). Describe the connections so that your class can be better classified. For example, design patterns are often composed of different classes with specific individual tasks that together provide a unity. 

## Describe your class based on numbers

Here are a few suggestions:

* Number of attributes: A few private attributes (3-5) are usually good. Only offer public attributes in rare cases.
* Number of public methods: Fewer public methods make your class easier to understand for consumers.
* Lines of Code: It depends on the programming language but less is faster to understand.

## Describe your class using the associated design pattern

| Design Pattern | Description |
| :--- | :--- |
| [Value object](https://en.wikipedia.org/wiki/Value_object) | Your class repesents a simple value like an amount of money. |
| [Data transfer object](https://en.wikipedia.org/wiki/Data_transfer_object) | Your class helps to exchange data between processes. |
| Parameter object | Bundle related parameters into one object. |
