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




# Diagrams
- [Use Case Diagram](#use-case-diagram)
- [Activity Diagram](#activity-diagram)
- [Class Diagram](#class-diagram)
- [Object Diagram](#object-diagram)
- [Sequence Diagram](#sequence-diagram)
- [Communication Diagram](#communication-diagram)
- [Timing Diagram](#timing-diagram)
- [Interaction Overview Diagram](#interaction-overview-diagram)
- [Component Diagram](#component-diagram)
- [Composite Structure](#composite-structure)
- [Package Diagram](#package-diagram)
- [State Machine Diagram](#state-machine-diagram)
- [Deployment Diagram](#deployment-diagram)


## Use Case Diagram
Use Case diagram defines how your system can solve a problem.  
It's considered for high level requirement analysis, it is so general and don't get in to details so much.  
It's also useful to make test cases when performing the testing.  
So when we have decided different pieces of our project, now we can draw Use Case diagrams for each piece of the project. e.g: One piece of the project is the Chat system as a whole... So one Use Case diagram can demonstrate that.

![Use Case Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_use-case.png)

**It's for whom**:
- Business stakeholders
- system designers
- developers

**Purpose**:
- Used to gather requirements of a system.
- Used to get an outside view of a system.
- Identify external and internal factors influencing the system.

**Important elements**:
- Actor (Something that interacts with the system, it can be human user, an internal/external application)
- Use case (A system functionality)
- System boundary (A box that use cases are drown inside of it and actors as external factors will be drawn outside of it)
- relationships (They help system designers to break the system's behavior into manageable chunks)

**Points to consider**:
- How to define an actor? Well, if answers to the following questions are 'YES', then what you wanna define, is probably an actor:
  1. Is it a human being? e.g: User.
  2. Is it something that you cannot modify in your system? e.g: ChatSystemDatabase.
- How to define a use case? A use case is actually a requirement and that's it. A use case must have a clear pass/fail criteria. e.g: Create a new conversation, send a message, etc...
- What is the `<<include>>` relationship? If two use cases have similar steps in their main flow, then instead of repeating ourselves we create another use case and connect it to the already existing two use cases via `<<include>>` relationship.
- What is the `<<extend>>` relationship? If we have some optional steps in a use case main flow, then we will create a brand new use case for those steps and connect the optional use case with `<<extend>>` relationship to the main use case. e.g: 'check message delivery' use case can have a `<<extend>>` relationship with 'send a message' use case. Because 'check message delivery' is an optional requirement in our system.

**Steps**:

1. Draw the Use Case diagram:
  - Draw actors.
  - Draw system boundary.
  - And finally draw use cases inside of the system boundary.
2. Write description for all of the use cases one by one:
  - Use Case Name: We write the name of the Use Case we're going to describe.
  - Related Requirement: Describe what the system shall and must do. We actually write a general description about all the works that system needs to do step by step.
  - Goal In Context: Describe the Use Case's general final goal.
  - Precondition: List the conditions that MUST be already true so that our system can start operating. e.g: Internet access, user must have an active account to be able to send messages, etc...
  - Successful End Condition: List successful conclusions that the system should achieve. e.g: staff receive messages from users successfully, secure users' accounts, etc...
  - Failed End Condition: List failed possible conclusions. We actually list the moments that system must end processing before it goes through the entire use case. e.g: user enters an invalid user/pass.
  - Actors: List the actors. e.g: user
  - Triggers: List the triggers. The list actually shows the events that happen before your system triggers. e.g: user creates a new conversation, sends a new message, etc...
  - Steps of execution(Main Flow): What may happen in the system step by step. e.g: 1. user logs in. 1A. user/pass is invalid. 1B. user exits. 2. user info will be validated. etc...
  - Extensions: List the optional functionalities that in the Diagram we have mentioned them by <<extend>> relationship. e.g: if pass is invalid 3 times (block the user)


## Activity Diagram
Activity diagram simply shows what actions occur to achieve an ultimate goal. It actually represents the flow from one activity to another activity.  
Like Use Case diagram, Activity diagram is also drawn from a very high level(It's basically for understanding business requirements rather than implementation details).  
Use Case Description and its steps of execution(main flow) and its extensions help us in drawing an Activity diagram.

![Activity Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_activity.png)

**It's for whom**:
- Business stakeholders
- system designers
- developers

**Purpose**:
- Modeling business requirements and the project work flow by using activities.
- Describe the parallel, branched and concurrent flow of the system.

**Important elements**:
- Action (Actions that system itself needs to take as it continues operating)
- Object Node (Shows data that is involved through the activity flow. And it's common to attach a note to the Object Node to document what information exactly that Object Node is going to represent)
- Object input/output Pin (It's a pin that attaches to an activity to show an activity's output or input data. It's like Object Node but the Object Node simply defines that such data is included in the activity process but pin emphasizes that such data is required and needs to move from one activity to another.)
- Decision/Merge (Shows a decision. A decision can have one input but multiple outputs, which means that after that the decision has been made, system will continue only one of the drawn outputs. Merge is also in the same diamond shape, but receives the outputs from the decision and has only one output to continue and hand it to the desire activity.)
- Fork/Join (When multiple activities are going to happen at the same time such as threads, we show it by Fork and unlike decision all outgoing paths are going to be followed. Join is also in the same shape of Fork, But like Merge receives inputs and has only one output.)
- Interruption Region (Demonstrates an activity that can end before the completion of the whole Activity diagram, it includes some activities plus the activity that is going to interrupt the system. So inside of the Interruption Region there's always an interrupting event. e.g: 'User Cancels' activity will be connected to 'Account Canceled' activity with an interrupting event.)
- Flow final node (it's a circle with an X inside of it. It shows that a flow ends without ending the whole process. It is needed in forks most of the times. When multiple activities are going to happen at the same time, using the fork notation, and some of the activities may have some other paths and their path is completely different so they won't come together in a join notation, then when they are finished with their own path and activity as their path won't end the whole system's process, we will show the end of their own path with the flow final node.)
- send/receive signal (an activity which is going to have some interaction with an external outside source. Send Signal sends info to an outside service to do a particular functionality and Receive Signal will receive some info from an outside source. Receive Signal comes after the Send Signal in most of the times.)
- Expansion Region (Represents some groups of items that need some sort of actions to be performed on all of them)
- Partition (It is called Swimlane too. Different activities may involve different participants. So partition will be used to show which participant is responsible for which action. e.g 'Ordering processing' activity requires 'shipping department' and 'accounts department' participants. With partition we separate these two participants and draw their related actions in them.)

**Points to consider**:
- What initial nodes can be in an Activity diagram? Well, Initial Nodes can be Initial State, Time Event, Receive Signal.
- If a time Event is an initial node in our diagram, then it means that we like to demonstrate a repeating activity, I mean an activity which repeats after the specified time again and again.
- In decision element we should make sure that only one guard evaluate to true because one of the outputs should continue.

**Steps**:

1. Draw the Activity diagram:
  - Start from the initial state.
  - Convert all the Use Case description's execution steps into a visualize picture.
  - And activities finally come to one final state to end the system process.


## Class Diagram
A collection of class diagrams represent the whole system.  
Classes in Class diagram show different objects that are going to be used in our system and let us know how they relate to each other.  
Elements in class diagram are actually in abstract form and represent the blue print.

![Class Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_class.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Describe responsibilities of a system.

**Important elements**:
- Class
- relationships(such as Inheritance, Composition, Aggregation, Association, Dependency)
- OCL (Object Constraint Language which is in three types generally: Invariant, Precondition, Postcondition)
- Interface

**Points to consider**:
- We can show Multiplicity in classes. Multiplicity allows us to declare certain rules for our classes' attributes that are going to represent a group of objects. e.g: 'Animal' class has 'owners' property that its type is 'Owner' class(so 'owners' property is representing a group of 'Owner' objects) and also our 'Animal' class can have at most 3 owners and they should be in order of ownership. So when we're representing this attribute, we can declare it like this: - owners: Owner[1..3] {ordered}
- Dependency and association relationships won't be shown in Class diagrams most of the times... They do exist most of the times and because of that reason drawing them all of over the place would increase unnecessary mess in our diagram.
- What is a template class? A template or parameterized class lets us to postpone the decision as to which classes the class is going to work with... I mean we know that the class's attributes and operations will use another class, but we still don't know what type that class might be. e.g a list class, it simply lists some items, but the class type of those items vary according to different situations.

**Steps**:

1. Draw the Class diagram:
  - Start drawing the base class(the very first class that will be initialized in our system) first.
  - Then move on and draw dependent classes of the base class and then the associated classes of the base class.
  - And we continue and draw all of the dependent and associated classes of all other classes till we represent all of the needed classes for doing the responsibility that is needed for the piece of the project that we're drawing the diagram for.


## Object Diagram
An Object represents an instance of a class.  
Object diagram is very simple and shows how different objects work together.  
An object diagram unlike the class diagram which is a blue print of the system, is a representation of a real life scenario. Elements are in concrete form to represent the real world object.  
Object diagram is a snapshot of the system at a particular moment. It's like taking a snap of a running train, you will find a static picture and can now analyze everything more accurate...

![Object Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_object.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Making the prototype of a system.
- Understand object behavior and their relationship from practical perspective.

**Important elements**:
- Object
- Link (Object diagram without links is useless. A link shows association between objects and the label of the link indicates its purpose.)

**Points to consider**:
- Consider only those instances which will cover the functionality(we should draw only the objects that have important data and association to prevent unnecessary complexity).

**Steps**:

1. Imagine all of the different scenarios that may happen based upon on the Actors decisions(Activity diagram helps us in this).
2. Draw Object diagrams for each of those scenarios.


## Sequence Diagram
Sequence diagram captures the time sequence of message flow(method call) from one object to another.  
It shows which methods are triggered and when they have been triggered exactly.

![Sequence Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_sequence.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Describe the message flow in the system, interaction among objects.

**Important elements**:
- Participant(it's an Object most of the times, but they can be any part of our system that is taking part in an interaction)
- Sequence Fragment(it's a box that contains some interactions... Has different types, that each type has a meaning. here are the different types: Optional, Negative, Alternative, Reference, Loop, Break, Parallel, Assert, Critical)

**Points to consider**:
- Draw only objects that are taking part in the interaction.
- Draw the sequence in which the messages are flowing in order.
- Use the right type of Sequence Fragments if they have been needed.

**Steps**:

1. Draw the Sequence diagram:
  - Start drawing from the very first message that is going to be triggered in the piece of system we're going to draw its diagram. (The use Case Main flow helps us in finding where to start and where to go after that)
  - Then we will draw the sender and the receiver participants.
  - And continue drawing the next interactions that should and shall be triggered so that the needed functionality gets done in our system.


## Communication Diagram
Communication diagram captures the organization of objects in a system taking part in the message flow, also shows time sequence of messages by a numbering technique.

![Communication Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_communication.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Describe the message flow in the system, structural organization of the objects, interaction among objects.

**Important elements**:
- Participant(it's an Object most of the times, but they can be any part of our system that is taking part in an interaction)

**Points to consider**:
- Draw only objects that are taking part in the interaction.
- Show the sequence in which the messages are flowing in order by a numbering technique. We show the sequence of messages by numbering them and show nested messages(the messages that are going to be triggered because of the last message. An existence of a a nested message is because of the existence of the last message call! So that's why we call them nested messages) by adding an additional decimal point to them, actually when a message hits a new participant a nested number will be added to it. e.g msgA is moving from object A to B, it will be 1.msgA(), then as the nested message that is going to move from B to C, will be 1.1.msgB(). Actually as soon as a message hits a new participant an additional decimal point will be added to it.

**Steps**:

1. Draw the Communication diagram:
  - Start drawing the very first object that is going to start the system. And all of the other participants. (The use Case Main flow helps us in finding where to start and where to go after that)
  - Now draw the links between each of the participants that are taking part in the interaction so that they can communicate with each other.
  - Then we write the messages one by one, by using a numbering technique.


## Timing Diagram
Timing diagram lists different actions that are going to happen for the piece of project that we're going to draw the diagram for and shows how long it takes each action to be processed and when each of them will be triggered.  
Use Case Description and its steps of execution(main flow) and its extensions help us in drawing activities(states) of the Timing diagram.  
Just like the Object diagram, we can draw a couple of Timing diagrams for different scenarios for just one piece of our project. Because different states may happen in different scenarios. And yes, most of the times it's also OK to draw one Timing diagram to show the timings when only common states are going to be triggered, it's actually up to us.

![Timing Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_timing.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Define the timing between different states in the system.
- Describe when events occur, how long it takes for participants to react and how long it takes for each individual interaction to get complete.

**Important elements**:
- Participant(it's an Object most of the times)
- states(actions)

**Points to consider**:
- if an object doesn't have any major interactions or states, then there's no reason to draw that object in a Timing diagram.
- Events and messages will be shown in the same way on a Timing diagram, because their difference is not as important as it is on the Sequence diagram. They will be shown only to trigger the state changes from one participant to another. The Sequence diagram already shows the messages that are passed between participants, so drawing the messages on the Timing diagram is actually a simple task.

**Steps**:

1. Find states, I mean different actions that are going to happen one after another in our system. We use the Use Case Description and its steps of execution(main flow) here.
2. Find the participants that these actions(states) belong to.
3. Match the states to participants. I mean now we write different states in order for each of the participants, to find out which state belongs to which participant and in what order the states would change step by step for each participant. This step, actually helps us when we're going to create methods for our participants(Objects).
4. Draw the Timing diagram:
  - We draw a table which contains participants in each raw. The order of the participants in rows is important, so in what order they should be? It's easy! We have already the Sequence diagram and all of the participants are listed at the top of that diagram, we only need to rotate the Sequence diagram 90 degrees counterclockwise and that's it! We now have the participants in right order in each row.
  - Now we start the Lifetime line of the first action of the first participant that starts the system... As soon as we reach an event or a message we draw it and connect it to the above participant's Lifetime line and again continue with the both Lifetime lines...
  - Then we move on and show(by using the Lifetime line) how long it takes each state of an participant to change to another state(each participant is going to have its own Lifetime line) for all of the participants.


## Interaction Overview Diagram
Interaction Overview diagram is so much similar to the Activity diagram, but instead of each activity in an Activity diagram, we draw interactions here.  
Like Activity diagram, Interaction Overview diagram is also drawn from a very high level(It lets us to see the bigger picture of the project flow and shows how several interactions work together to implement a system concern).  
It uses different interaction diagrams(Sequence, Communication, Timing) and ties them together to make a single complete picture of the interactions that shows a particular system functionality.

![Interaction Overview Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_interaction-overview.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Modeling business requirements and the project work flow by using interactions.
- Describe the parallel, branched and concurrent flow of the system.

**Important elements**:
- Interaction(It's a box that contains a part of Sequence or Communication or Timing diagrams that we've already drawn)

**Points to consider**:
- We should decide what kind of interaction diagram we should use for each individual interactions in the Interaction Overview diagram according to what is important for us to show for that interaction. e.g when we want to show an interaction, we should decide for that interaction, message order is important or the timing constraint, and according to that we finally decide which type of iteration diagram we should draw for it.

**Steps**:

1. Draw the Interaction Overview diagram:
  - We start drawing from the initial node (Activity diagram can help us in finding out where to start and what interactions we should draw)
  - Now we draw all of the interactions, and after that all of the participants will be known too.
  - Now that we know all the participants, we write their names in the lifeline list in the interaction overview's title bar.
  - And finally, we draw the actual flow of control between the interactions, just like how we draw the flow in the Activity diagram.


## Component Diagram
Component diagram does not describe the functionality of the system but it describes the components used to make those functionalities.  
It shows us the system from a more global perspective to see what components do we have and how they work together.  
Components themselves can be different pieces of our project, or maybe some related classes that altogether do a particular service.  
Components are used to help us organize our system into manageable, reusable and swappable pieces of software.

![Component Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_component.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Describe the organization and relationships of the components.
- Model database schema, executables of an application, system's source code.

**Important elements**:
- Component(it's a reusable piece of code that includes classes and interfaces. It takes care of a more heavier responsibility than a single class, it actually does a service. A component must communicate through interfaces and clearly show what are its inputs and outputs)
- Required/Provided Interface(Describe the service that a component offers. Required interface is the one that is required for a component to function and the provided interface may not be needed for a component, though most of the times they do exist as a component gets something and provides something else)
- Port(Used to represent related interfaces attached to a component. e.g a component can have more than one provided interfaces, these interfaces will be attached to the component by port)

**Points to consider**:
- Since components have great responsibilities and are the major players in our systems, it's important to keep them loosely coupled, so that changes to a component do not affect the rest of the system. So that's why they are accessed through interfaces as an interface separates a behavior from its implementation.
- What is the difference between Black-Box and White-Box component views? White-Box component view shows the internal structure of a component(what object the component contains) and focuses on the inner workings of the component to show how it achieves its goal through the classes that it uses, whereas Black-Box view shows the big picture of the components working together.

**Steps**:

1. Draw the Component diagram:
  - It doesn't matter which component we're going to start drawing with. Just draw one with its interfaces.
  - And then we will draw other related components next to the one that we've just drawn(if there's any related component of course). I mean we draw the component which its Provided interface is the Required interface of the last component...
  - And we continue drawing all other components of our system in order to make a more global look of the whole system.


## Composite Structure
Composite Structure models how objects work together inside a class. It mainly shows the internal structure of a class.  
Sometimes the primary UML diagrams don't capture some certain aspects of your system, that's what Composite Structure is going to do.

![Composite Structure](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_composite-structure.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- Describe the internal structure of a class.
- Show design patterns in your system and how objects cooperate to achieve a goal.

**Important elements**:
- Part(Object which is used in a class)
- Property(It's an outside data that the class has, so the data of the property for different instances of a class is the same, but data of the parts of them may be different. e.g different instances of 'Conversation' class may have different 'summary' values, but all of them share one 'Theme' with the same exact value)
- Singular Instance(It's a specific constant which is shared across the whole instances of a class. e.g 'ApplicationName' can be a constant which is always the same and there's only one single instance of it available in all 'Conversation' instances)
- Port(Connects our classes to other outside classes and interfaces. Because as we know a class can also have some Provided/Required interfaces. ports actually show distinct uses of a class)
- Collaboration(Shows how objects are going to work together to accomplish a task. It actually shows us what objects are involved to do a specific task and that task can also be temporarily. Objects that are involved in a collaboration actually have some temporarily roles, so yes, another collaboration which is going to demonstrate another task may use the very same objects that are mentioned in an older collaboration, in new roles and related to each other differently to do the new task... e.g to do 'show a list of conversations' task, 'CoversationsHolder' and 'Conversation' instances collaborate together)

**Points to consider**:
- When drawing a part in the class, We also write the number of instances(multiplicity) of it. e.g a 'Conversation' class may have many 'Message' instances but only has one 'summary' instance initialized in it.

**Steps**:

1. Draw the Composite Structure of different classes.
2. Draw Collaborations for different tasks.


## Package Diagram
Packages group similar classes. Package Diagram shows the dependencies between classes.

![Package Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_package.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- To group classes of similar functionality.
- To show the dependencies between classes.

**Important elements**:
- Package

**Points to consider**:
- Dependency arrows(import, access) show that a package depends on another package or a class inside of another package. Imported elements by 'import' arrows, have public visibility in the importing package, so they can get passed on with further imports, whereas accessed elements do not. e.g if package A imports package B(B itself imports C), then package A also has access to package C, but if B used 'access' instead of 'import' arrow while importing C, then A couldn't access C.But let me also mention that many modelers don't bother about using 'import' or 'access' dependencies, they just use a generic dependency arrow without mentioning its type.
- When showing classes we can also mention the package that they belong to(utils::Scroller) so that in our diagrams when we mention two different classes that have the same name, we can distinguish them from one another easily by referring to their package name.
- We should avoid cyclical package dependencies... This is the time that package A, depends on package B and B also depends on A... This is not good as a change in one package, heavily affects the other one. So to avoid this we should consider depending in the order of stability, I mean a package should depend only on packages more stable than itself. In this way, an unstable package depends on many other packages and a stable package depends on few packages.

**Steps**:

1. Draw the Package diagram:
  - We just think about different pieces of our project, find out what classes related to each other and put them in one package.
  - Then with dependency arrows, show what packages import other packages in the system.


## State Machine Diagram
State Machine Diagram describes different states of an object in a system, and the object may act differently according to its current state.  
These states are controlled by external or internal events.  
Generally it defines states and it is used to model lifetime of an object. It's useful to model reactive systems(systems that respond to external or internal events).

![State Machine Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_state-machine.png)

**It's for whom**:
- system designers
- developers

**Purpose**:
- To model life time of a reactive system.

**Important elements**:
- State
- Transition Arrow

**Points to consider**:
- How states look like in code? Imagine our class has a 'status' attribute and the states that we draw in the diagram will be the values of that attribute. Transitions occur when methods of our class are invoked.
- What is State internal behavior? It's a state that itself changes some internal states inside of itself. When drawing a State internal behavior, we write 'internal behavior' which contains: 'entry' point(shows what should happen, I mean what event should be called in order to enter the whole State internal behavior), 'do'(An ongoing job that we're going to do in this state) and 'exit'(what should happen when we're exiting the whole state, I mean after the 'do' job). Unlike 'do' behavior, 'entry' and 'exit' behaviors can't be interrupted('do' will be interrupted when the 'internal transitions' guard evaluates to true). We also write 'internal transitions' exactly like normal transition arrows and they show what the state does if the guard statement of the transition evaluates to true.
- What is Composite state? It shows the time that two states are going to happen at the same time.

**Steps**:

1. Draw the State Machine diagram:
  - Think about from which event and state the system is going to get started and draw the needed state.
  - Then we continue and draw all of the other changing states.


## Deployment Diagram
Deployment Diagram shows how software and hardware work together.  
Generally every project has some business requirements and budget, an efficient deployment diagram should meet these types of requirements and be designed in a cost effective way. So that's why Deployment diagram is useful, it can for example help us to see what kind of server do we need for our project, etc.

![Deployment Diagram](https://github.com/imalitavakoli/learn-uml2/blob/master/images/diagram_deployment.png)

**It's for whom**:
- system designers
- developers
- system engineers

**Purpose**:
- Describe runtime processing nodes(By nodes, I mean physical hardwares).
- Model hardware details for a client/server system.

**Important elements**:
- Nodes(It can be anything that we consider as an hardware or an executable environment. e.g Computer, Server, Hard Drive, Router, Firewall)

**Points to consider**:
- When nodes are actually software, we may specify that by Stereotypes. Such as `<<executionEnvironment>>` (e.g server), `<<database>>` (e.g MySQL 5.5), `<<schema>>`, `<<artifact>>`.
- When showing for example some `<<artifact>>` (artifacts can be any type of file such as txt, xml, etc...) inside of a `<<device>>` (like a PC or server) we should consider to show only important artifacts that are actually useful for our system designers and developers to consider in the Deployment diagram... We don't want to draw unnecessary stuff here and there to make our diagram unnecessarily complex.
- What is `<<executionEnvironment>>`? It's where our software and codes are going to be executed in a `<<device>>`. Imagine the following example: We draw a `<<device>>` like a Smart Phone and inside of it we draw another node as a `<<executionEnvironment>>`. And yes, inside of it we can also mention our artifact which implements a component(the component makes sure that our software which is coming into the device fits the requirements of the device and it can do what it's suppose to do)
- What is `<<deployment spec>>`? It's a special artifact that specifies how another artifact is deployed to a node. It provides information that allows another artifact to run successfully in its environment. It often has some properties like which class should be executed in the execution environment and which methods of the class can be called. e.g a configuration file which its parameters should be defined before the software can be executed.

**Steps**:

1. Draw the Deployment diagram:
  - We start drawing from the first device that our software is going to be executed inside of it.
  - Then continue and draw any other environments and databases that the device communicates with to run our software successfully.




# What's next?
In this tutorial I tried to explain what is UML, why it is useful, how to start a project using UML and what notations and diagrams does it have.  
So you wanna learn more about every aspects of UML? Here are some great resources that help you on your way:

* [Learning UML 2.0](http://shop.oreilly.com/product/9780596009823.do) teaches you UML from the basics.

* [UML 2.0 in a Nutshell](http://shop.oreilly.com/product/9780596007959.do) gets into details and makes you an UML hero.
