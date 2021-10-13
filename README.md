# JAVA_AND_OOPS_1

Java programming language was originally developed by Sun Microsystems
– by James Gosling
– released in 1995 as core component of Sun Microsystems
– Java platform (Java 1.0 [J2SE]).
– Java Standard Edition 7 Update 25 (1.7.25) (June 18, 2013)

Object-Oriented Programming (OOP) uses "objects" to model realworld objects.
Object-Oriented Programming (OOP) consist of some important concepts namely Encapsulation,
Polymorphism, Inheritance and Abstraction. These features are generally referred to as the OOPS concepts.

Encapsulation
Encapsulation is the process of wrapping up of data (properties) and behavior (methods) of an object into a
single unit; and the unit here is a Class (or interface).
Encapsulate in plain English means to enclose or be enclosed in or as if in a capsule. In Java, everything is
enclosed within a class or interface, unlike languages such as C and C++ where we can have global variables
outside classes.
Encapsulation enables data hiding, hiding irrelevant information from the users of a class and exposing only
the relevant details required by the user. We can expose our operations hiding the details of what is needed
to perform that operation.
Inheritance
Inheritance describes the parent child relationship between two classes.
A class can get some of its characteristics from a parent class and then add more unique features of its
own. For example, consider a Vehicle parent class and a child class Car. Vehicle class will have properties
and functionalities common for all vehicles. Car will inherit those common properties from the Vehicle class
and then add properties which are specific to a car.
In the above example, Vehicle parent class is known as base class or superclass. Car is known as derived
class, Child class or subclass.
Java supports single-parent, multiple-children inheritance and multilevel inheritence (Grandparent-> Parent -
> Child) for classes and interfces.
Java supports multiple inheritance (multiple parents, single child) only through interfaces. This is done to
avoid some confusions and errors such as diamond problem of inheritance.
Plymorphism
The ability to change form is known as polymorphism. Java supports different kinds of polymorphism like
oveloading and overriding.
Overloading
The same method name (method overloading) or operator symbol (operator overloading) can be used in
different contexts.
Java doesn't allow operator overloading except that "+" is overloaded for class String. The "+" operator can
be used for addition as well as string concatenation.
Overloading may be also called compile time polymorphism.
Overriding (or subtype polymorphism)
We can override an instance method of parent class in the child class.
When you refer to a child class object using a Parent reference (e.g. Parent p = new Child()) and invoke a
method, the overriden child class method will be invoked. Here, the actual method called will depend on the
object at runtime, not the reference type.
Overriding is not applicable for static methods or variables (static and non-static). In case of variables (static
and non-static) and static methods, when you invoke a method using a reference type variable, the method or
variable that belong to the reference type is invoked.
Overriding may be also called runtime polymorphism.
Abstraction
In plain English, abstract is a concept or idea not associated with any specific instance and does not have a
concrete existence.
Abstraction in Object Oriented Programming refers to the ability to make a class abstract.
Abstraction captures only those details about an object that are relevant to the current perspective, so that the
programmer can focus on a few concepts at a time.
Java provides interfaces and abstract classes for describing abstract types.
 An interface is a contract or specification without any implementation. An interface can't have
behavior or state.
 An abstract class is a class that cannot be instantiated, but has all the properties of a class including
constructors. Abstract classes can have state and can be used to provide a skeletal implementation




What is SDLC?
SDLC is a process followed for a software project, within a software organization. It consists of a detailed plan describing how to develop, maintain, replace and alter or enhance specific software. The life cycle defines a methodology for improving the quality of software and the overall development process.

SDLC Models
There are various software development life cycle models defined and designed which are followed during the software development process. These models are also referred as Software Development Process Models". Each process model follows a Series of steps unique to its type to ensure success in the process of software development.

Following are the most important and popular SDLC models followed in the industry −

Waterfall Model
Iterative Model
Spiral Model
V-Model
Big Bang Model
Other related methodologies are Agile Model, RAD Model, Rapid Application Development and Prototyping Models.
