<h1>Design Pattern - Factory Pattern</h1>

Factory pattern is one of the most used design patterns in Java. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.

In Factory pattern, we create object without exposing the creation logic to the client and refer to newly created object using a common interface.

<h2>Implementation</h2
We're going to create a Shape interface and concrete classes implementing the Shape interface. A factory class ShapeFactory is defined as a next step.

FactoryPatternDemo, our demo class will use ShapeFactory to get a Shape object. It will pass information (CIRCLE / RECTANGLE / SQUARE) to ShapeFactory to get the type of object it needs.

![factory_pattern_uml_diagram](https://user-images.githubusercontent.com/79799727/203266619-cfb0d773-4537-43b0-87c6-daca0bbed9b3.jpeg)


Sinhala YouTube Tutorial - https://www.youtube.com/watch?v=dhGjPp1Nxgs&list=PPSV

