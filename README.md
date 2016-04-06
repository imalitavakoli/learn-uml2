# Learn UML2.\* in simple terms

**Unified Modeling Language** helps you to document your projects and have a full overview of the whole project.  
It helps you build software systems efficiently.  
In this tutorial I tried to summarize everything and have explained all of the important elements of UML, explained almost every aspects of it and all of the needed diagrams... All explained in simple terms for dummies like me :smile:

So if you're ready, then let's dive in!




# Introduction

## For whom this tutorial is?
For anyone interested in learning UML 2.0! If you also have a little bit knowledge about object-oriented Design (OOD) it will help you to grab the basics faster.  
But if you are not also familiar with OOD or don't know any programming language... Still there's no problem, as far as you're interested and eager to learn UML, that's good enough :thumbsup:


## Why to learn UML?
> UML helps you build better software systems. It's like a road map that shows you exactly where to go to reach your destination safe and sound.  
\- Ali Tavakoli

So you may say that I myself can grab a piece of paper and start sketching my own map for my project, I don't need to learn UML! Well, you might be right! But you would understand that soon, you have been mistaken when you are at the middle of a broken project and have lost so much budget and time!  
That's why UML has been invented! It's a formal language, concise, comprehensive, scalable, built based on lots of experiences and in overall it's the standard.


## What is UML?
UML, Unified Modeling Language, is a graphical way of describing software systems.
**Created for anyone who is interested to understand the system** no matter what the person's job or position is! Such as developers, users and business stakeholders.

UML can be used in 2 degrees mainly:

- **UML Sketching**: Good for users and business stakeholders to understand what the system is going to do in overall and what are the requirements.

- **UML Blueprint**: Good for developers to understand how the system is going to work technically in details.




# How to get started

## How to start a project?
To start a project, you should decide what Software Development and Planning process you wanna take.

Software Development processes:

- **Waterfall**: You will do the following step by step for the whole project: Analysis, design, coding, testing.  
Each of these steps should be completely done before you proceed to the next one. But the problem with this process is that when a change happens at the middle of the project then you will face huge problems.

- **Iterative**: This process is the most common. You first define different pieces for your project and then do all the steps mentioned in the Waterfall process for each piece. Iterative process accepts that change may happen so by defining pieces if a change happens, you only need to take actions on the piece of project that you're currently working on and it doesn't effect the whole system.

Software Planning processes:

- **Predictive**: You know all of the project requirements, so you plan everything at the beginning of the project and then start.

- **Adaptive(Agile Development)**: In this type of process you accept that the project requirements may change as you go on...  
So as an adapter you work with users continually to edit the project requirements(for every piece of the project) and add additional functionalities throughout the process. Agile methods use Iterative development process. It uses iterations in short bursts and its goal is to minimize the risks, save time and let you always have a working system as each piece of the project is going to meet its requirements.


## Now from what perspectives should I look at my project?
Any real world system is used by different users. Users can be developers, testers, business people, analysts and many more.
So we should visualize the system from different viewer's perspective to design the best possible system.

![Kruchten 4+1 view model](https://github.com/imalitavakoli/learn-uml2/blob/master/images/Kruchten-4+1-view-model.png)

**Kruchten 4+1 view model** shows that a project has 5 views:

- **Logical View**: Shows what a system is made up and how they interact with each other. Diagrams: Class, Object, State Machine, Interactions.

- **Process View**: Shows what must happen within the system and how it must happen. Diagrams: Activity.

- **Development View**: Shows how system parts are organized into modules and components. Diagrams: Package, Component.

- **Physical View**: Shows how abstract parts of the system map into the deployed system in real world. Diagrams: Deployment.

- **Use Case View**: Shows what the system must and should do generally. All of the other views rely on this view, that's why this view model is called 4+1. Diagrams: Use Case.

[Click here](http://www3.software.ibm.com/ibmdl/pub/software/rational/web/whitepapers/2003/Pbk4p1.pdf) to learn more about Kruchten 4+1 view model.


## What are Diagrams?
UML has different types of diagrams that each diagram shows the system from different perspectives.
Any complex system is best understood by making some kind of diagrams or pictures.

There are two broad categories of diagrams, here in this part, I only mention the most important diagrams, but as we continue we will cover all of the diagrams:

- **Structural Diagrams**: (Represent the static aspect of the system)

  - Class diagram: It's the most common diagram. It represent the object oriented view of a system.

  - Object Diagram: It's an instance of class diagram. The usage of object diagrams is similar to class diagrams but they are used to build prototype of a system from practical perspective.

  - Component Diagram: Represents a set of components and their relationships. During designing a system, classes, interfaces and etc are arranged in different groups depending upon their relationship. Now these groups are known as components.

  - Deployment Diagram: These diagrams are a set of nodes and their relationships. These nodes are physical entities where the components are deployed.

- **Behavioral Diagrams**: (These diagrams basically capture the dynamic aspect of a system)

  - Use case diagram: These are a set of use cases, actors and their relationships. A use case represents a particular functionality of a system.

  - Sequence Diagram: Sequence diagram is used to visualize the sequence of calls in a system to perform a specific functionality.

  - Communication Diagram: It's somehow like the Sequence Diagram. But its goal is to represent the structural organization of a system and the messages sent/received.

  - State Machine Diagram: Any real time system is expected to be reacted by some kind of internal/external events. These events are responsible for state change of the system.

  - Activity Diagram: Activities are nothing but the functions of a system. Numbers of activity diagrams are prepared to capture the entire flow in a system.


## What are Notations?
Notations will be used in UML Diagrams.
They describe the purpose of the model, things and relationships. Each type of notation looks different.
Here I explain the most important notations and as we continue and start learning more about each diagram, you will learn all of the notations.

![UML Notations](https://github.com/imalitavakoli/learn-uml2/blob/master/images/notations.png)

- **Structural**:

  - Class Notation: Represents an object. Object can be anything having properties and responsibility.

  - Object Notation: The instance of a class.

  - Interface Notation: Represented by a circle most of the times. It describes functionality without implementation. It's actually a template that defines different functions and not their implementation.

  - Collaboration Notation: Represented by a dotted eclipse. It represents responsibilities.

  - Use case Notation: Represented by an eclipse. But unlike Collaboration Notation inside of the eclipse there's a name instead of listing some responsibilities(Or drawing the objects that play role in that responsibility). It is used to capture high level functionalities of a system.

  - Actor Notation: It can be defined as some internal or external entity that interacts with the system. It is mostly used in a use case diagram.

  - Initial State Notation: It shows the start of a process. It is used in almost all diagrams.

  - Final State Notation: It show the end of a process. It is used in almost all diagrams.

  - Component Notation: It is used to represent any part of a system for which UML diagrams are made.

  - Node Notation: It represents a physical part of a system like server, network etc.

- **Behavioural**:

  - Interaction Notation: It is basically message exchange between two UML components. It represents communication among the components of a system.

  - State machine Notation: It describes the different states of a component in its life cycle.

- **Grouping**:

  - Package Notation: It is used to wrap the components of a system.


- **Annotational**:

  - Note Notation: It captures any additional comments that are not captured in the diagram. It's like a comment in code. A note can be attached to an element by a dotted line.


- **Relationships**:

  - Dependency Notation: A class depends on another class. Actually it shows that a class has an attribute of another class type.

  - Association Notation: A class references another class. Actually it shows that a class is related to another class but they don't necessarily have attributes to show this relationship... e.g 'Teacher' and 'Student' classes, although 'Teacher' class has no attribute that refer to students, but we do know that in reality a teacher do have students... And also 'School' class has 'teachers' and 'students' properties that now make those two classes related to each other.

  - Aggregation Notation: A class contains another class. But if the container(ClassRoom) is destroyed, the contained(Chair) is not. Actually the ClassRoom owns the Chair. Aggregation is a more stronger relationship than the previous mentioned relationships.

  - Composition Notation: A class contains another class. And if the container(ClassRoom) is destroyed, the contained(Wall) is also. Actually Wall is part of the ClassRoom. Composition is even more stronger than the Aggregation relationship.

  - Inheritance Notation: A class extends or implements another class. Actually the inherited class itself is the parent class because it also has all of the parent's attributes and operations. Actually inheritance is the most strongest relationship.


## What are Stereotypes?
Stereotypes will be used in UML Diagrams.  
A Stereotype signify a special use and can be applied to almost any element.  
It modifies the meaning of an element and describes the element's role in the model.  
Here is a sample Stereotype that defines the element which it is written on is an actor: `<<actor>>`

UML has defined some standard Stereotypes that help us to name elements better based on their responsibilities:

- Applied to classes: Utility(A class that represents a utility services through static methods, like a Math class).

- Applied to components: Service(A statless component that computes a value, like a web service), subsystem(a subordinate system of a larger system).

- Applied to artifacts: Executable(A physical file that is executable, like .exe), File(A physical file used by the system, like a configuration .txt file), Library(A lib file, like .dll or .js files), source(A source file containing the main codes, like .js).

And **what is a Tagged Value?** Well, a Stereotype can contain extra information about the element that it's applied to, a Tagged Value shows that extra information. In most of the times a Tagged Value defines what roles a specific Stereotype must obey. A Tagged Value will be drawn in the diagrams using the similar notation to notes. It includes the associated Stereotype name with the settings of the Tagged Value, then will be attached to the Stereotyped element using a dotted line with a circle at the element end.


## What is OCL?
OCL, Object Constraint Language, helps us express constraints in our models. For example when we like to define a rule for an attribute of a class in the Class diagram, we write: `{id >= 0}`
OCL not only helps us easily understand constraints in our models but also helps automated tools to understand them.
We don't necessarily need to use OCL in our models and can simply use Notes and write constraints in natural language, but as we know natural language is ambiguous but OCL is a single formal constraint language, and that's why most of the modelers prefer it.
In UML diagrams, OCL is primarily used to write constraints in Class diagrams and guard conditions in State and Activity diagrams.

OCL has four built-in types: `Boolean`(true; false), `Integer`(1; -20), `Real`(5.4), `String`("Hello!")
OCL has the basic arithmetic, logical and comparison operators:
- Applied to Integer, Real: `+, -, *, /, abs(), max(), min(), <, >, <=, >=`
- Applied to All types: `=, <>`
- Applied to Boolean: `and, or, xor, not`
- Applied to String: `concat(), size(), substring(), toInteger(), toReal()`

There are three types of constraints:
- Invariant: It's a condition that must always be true, it's defined on class attributes.
- Precondition: They show that a pre-condition must be true before a method of a class is executed.
- Postcondition: Shows that a post-condition must be true after a method of a class has been executed to show that the method has done what it supposed to do correctly.


## From which diagram should I get started?
Some diagrams depend on another ones, for example Object diagram depends on Class diagram and Deployment diagram depends on Component diagram... So it is good to know which diagram we should draw first.  
Although UML does not push any particular system development... But there are some common steps that you can take.  
So **I myself prefer to draw Diagrams in the following order**: Use Case, Activity, Class, Object, Component, Package, Interactions, State Machine, Deployment.

And yes, at the very beginning we define different pieces of our project and then we draw all of the needed diagrams for each piece of the project. And that's it! We would have a complete road map of our project. We have actually documented our project from all different perspectives. So that if we have ever decided to change our project's technology in the future or needed to upgrade something in it or even changed our developer's team totally... There's no worries! We have designed our whole project with UML, so we can easily do all of these stuff without messing up with the project.
