



# Architecture

UML plays an important role in defining different perspectives of a system. These perspectives are −

-   Design
-   Implementation
-   Process
-   Deployment

The center is the **Use Case** view which connects all these four. A **Use Case** represents the functionality of the system. Hence, other perspectives are connected with use case.

**Design** of a system consists of classes, interfaces, and collaboration. UML provides class diagram, object diagram to support this.

**Implementation** defines the components assembled together to make a complete physical system. UML component diagram is used to support the implementation perspective.

**Process** defines the flow of the system. Hence, the same elements as used in Design are also used to support this perspective.

**Deployment** represents the physical nodes of the system that forms the hardware. UML deployment diagram is used to support this perspective.

# Model type

## Structural Modeling

Structural modeling captures the static features of a system. They consist of the following −

-   Classes diagrams
-   Objects diagrams
-   Deployment diagrams
-   Package diagrams
-   Composite structure diagram
-   Component diagram

Structural model represents the framework for the system and this framework is the place where all other components exist. Hence, the class diagram, component diagram and deployment diagrams are part of structural modeling. They all represent the elements and the mechanism to assemble them.

The structural model never describes the dynamic behavior of the system. Class diagram is the most widely used structural diagram.

## Behavioral Modeling

Behavioral model describes the interaction in the system. It represents the interaction among the structural diagrams. Behavioral modeling shows the dynamic nature of the system. They consist of the following −

-   Activity diagrams
-   Interaction diagrams
-   Use case diagrams

All the above show the dynamic sequence of flow in a system.

## Architectural Modeling

Architectural model represents the overall framework of the system. It contains both structural and behavioral elements of the system. Architectural model can be defined as the blueprint of the entire system. Package diagram comes under architectural modeling.

# Basic Notations
[UML - Basic Notations - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_basic_notations.htm)

## Class Notation

UML _class_ is represented by the following figure. The diagram is divided into four parts.

-   The top section is used to name the class.
-   The second one is used to show the attributes of the class.
-   The third section is used to describe the operations performed by the class.
-   The fourth section is optional to show any additional components.

![Class Notation](https://www.tutorialspoint.com/uml/images/notation_class.jpg)

Classes are used to represent objects. Objects can be anything having properties and responsibility.

## Object Notation

The _object_ is represented in the same way as the class. The only difference is the _name_ which is underlined as shown in the following figure.

![Object Notation](https://www.tutorialspoint.com/uml/images/notation_object.jpg)

As the object is an actual implementation of a class, which is known as the instance of a class. Hence, it has the same usage as the class.

## Interface Notation

Interface is represented by a circle as shown in the following figure. It has a name which is generally written below the circle.

![Interface Notation](https://www.tutorialspoint.com/uml/images/notation_interface.jpg)

Interface is used to describe the functionality without implementation. Interface is just like a template where you define different functions, not the implementation. When a class implements the interface, it also implements the functionality as per requirement.

## Collaboration Notation

Collaboration is represented by a dotted eclipse as shown in the following figure. It has a name written inside the eclipse.

![Collaboration Notation](https://www.tutorialspoint.com/uml/images/notation_collaboration.jpg)

Collaboration represents responsibilities. Generally, responsibilities are in a group.

## Use Case Notation

Use case is represented as an eclipse with a name inside it. It may contain additional responsibilities.

![Use case Notation](https://www.tutorialspoint.com/uml/images/notation_usecase.jpg)

Use case is used to capture high level functionalities of a system.

## Actor Notation

An actor can be defined as some internal or external entity that interacts with the system.

![Actor Notation](https://www.tutorialspoint.com/uml/images/notation_actor.jpg)

An actor is used in a use case diagram to describe the internal or external entities.

## Initial State Notation

Initial state is defined to show the start of a process. This notation is used in almost all diagrams.

![Initial state Notation](https://www.tutorialspoint.com/uml/images/notation_initialstate.jpg)

The usage of Initial State Notation is to show the starting point of a process.

## Final State Notation

Final state is used to show the end of a process. This notation is also used in almost all diagrams to describe the end.

![Final state Notation](https://www.tutorialspoint.com/uml/images/notation_finalstate.jpg)

The usage of Final State Notation is to show the termination point of a process.

## Active Class Notation

Active class looks similar to a class with a solid border. Active class is generally used to describe the concurrent behavior of a system.

![Active class Notation](https://www.tutorialspoint.com/uml/images/notation_activeclass.jpg)

Active class is used to represent the concurrency in a system.

## Component Notation

A component in UML is shown in the following figure with a name inside. Additional elements can be added wherever required.

![Component Notation](https://www.tutorialspoint.com/uml/images/notation_component.jpg)

Component is used to represent any part of a system for which UML diagrams are made.

## Node Notation

A node in UML is represented by a square box as shown in the following figure with a name. A node represents the physical component of the system.

![Node Notation](https://www.tutorialspoint.com/uml/images/notation_node.jpg)

Node is used to represent the physical part of a system such as the server, network, etc.

### Behavioral Things

Dynamic parts are one of the most important elements in UML. UML has a set of powerful features to represent the dynamic part of software and non-software systems. These features include _interactions_ and _state machines_.

Interactions can be of two types −

-   Sequential (Represented by sequence diagram)
-   Collaborative (Represented by collaboration diagram)

## Interaction Notation

Interaction is basically a message exchange between two UML components. The following diagram represents different notations used in an interaction.

![Interaction Notation](https://www.tutorialspoint.com/uml/images/notation_interaction.jpg)

Interaction is used to represent the communication among the components of a system.

## State Machine Notation

State machine describes the different states of a component in its life cycle. The notations are described in the following diagram.

![State machine Notation](https://www.tutorialspoint.com/uml/images/notation_statemachine.jpg)

State machine is used to describe different states of a system component. The state can be active, idle, or any other depending upon the situation.

### Grouping Things

Organizing the UML models is one of the most important aspects of the design. In UML, there is only one element available for grouping and that is package.

## Package Notation

Package notation is shown in the following figure and is used to wrap the components of a system.

![package Notation](https://www.tutorialspoint.com/uml/images/notation_package.jpg)

### Annotational Things

In any diagram, explanation of different elements and their functionalities are very important. Hence, UML has _notes_ notation to support this requirement.

## Note Notation

This notation is shown in the following figure. These notations are used to provide necessary information of a system.

![Note Notation](https://www.tutorialspoint.com/uml/images/notation_note.jpg)

### Relationships

A model is not complete unless the relationships between elements are described properly. The _Relationship_ gives a proper meaning to a UML model. Following are the different types of relationships available in UML.

-   Dependency
-   Association
-   Generalization
-   Extensibility

## Dependency Notation

Dependency is an important aspect in UML elements. It describes the dependent elements and the direction of dependency.

Dependency is represented by a dotted arrow as shown in the following figure. The arrow head represents the independent element and the other end represents the dependent element.

![Dependency Notation](https://www.tutorialspoint.com/uml/images/notation_dependency.jpg)

Dependency is used to represent the dependency between two elements of a system

## Association Notation

Association describes how the elements in a UML diagram are associated. In simple words, it describes how many elements are taking part in an interaction.

Association is represented by a dotted line with (without) arrows on both sides. The two ends represent two associated elements as shown in the following figure. The multiplicity is also mentioned at the ends (1, *, etc.) to show how many objects are associated.

![Association Notation](https://www.tutorialspoint.com/uml/images/notation_association.jpg)

Association is used to represent the relationship between two elements of a system.

## Generalization Notation

Generalization describes the inheritance relationship of the object-oriented world. It is a parent and child relationship.

Generalization is represented by an arrow with a hollow arrow head as shown in the following figure. One end represents the parent element and the other end represents the child element.

![Generalization Notation](https://www.tutorialspoint.com/uml/images/notation_generalization.jpg)

Generalization is used to describe parent-child relationship of two elements of a system.

## Extensibility Notation

All the languages (programming or modeling) have some mechanism to extend its capabilities such as syntax, semantics, etc. UML also has the following mechanisms to provide extensibility features.

-   Stereotypes (Represents new elements)
-   Tagged values (Represents new attributes)
-   Constraints (Represents the boundaries)

![Extensibility Notation](https://www.tutorialspoint.com/uml/images/notation_extensibility.jpg)

Extensibility notations are used to enhance the power of the language. It is basically additional elements used to represent some extra behavior of the system. These extra behaviors are not covered by the standard available notations.

# Diagrams
[UML - Standard Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_standard_diagrams.htm)

## Structural Diagrams

The structural diagrams represent the static aspect of the system. These static aspects represent those parts of a diagram, which forms the main structure and are therefore stable.

These static parts are represented by classes, interfaces, objects, components, and nodes. The four structural diagrams are −

-   Class diagram
-   Object diagram
-   Component diagram
-   Deployment diagram

### Class Diagram

Class diagrams are the most common diagrams used in UML. Class diagram consists of classes, interfaces, associations, and collaboration. Class diagrams basically represent the object-oriented view of a system, which is static in nature.

Active class is used in a class diagram to represent the concurrency of the system.

Class diagram represents the object orientation of a system. Hence, it is generally used for development purpose. This is the most widely used diagram at the time of system construction.

### Object Diagram

Object diagrams can be described as an instance of class diagram. Thus, these diagrams are more close to real-life scenarios where we implement a system.

Object diagrams are a set of objects and their relationship is just like class diagrams. They also represent the static view of the system.

The usage of object diagrams is similar to class diagrams but they are used to build prototype of a system from a practical perspective.

### Component Diagram

Component diagrams represent a set of components and their relationships. These components consist of classes, interfaces, or collaborations. Component diagrams represent the implementation view of a system.

During the design phase, software artifacts (classes, interfaces, etc.) of a system are arranged in different groups depending upon their relationship. Now, these groups are known as components.

Finally, it can be said component diagrams are used to visualize the implementation.

### Deployment Diagram

Deployment diagrams are a set of nodes and their relationships. These nodes are physical entities where the components are deployed.

Deployment diagrams are used for visualizing the deployment view of a system. This is generally used by the deployment team.

**Note** − If the above descriptions and usages are observed carefully then it is very clear that all the diagrams have some relationship with one another. Component diagrams are dependent upon the classes, interfaces, etc. which are part of class/object diagram. Again, the deployment diagram is dependent upon the components, which are used to make component diagrams.

## Behavioral Diagrams

Any system can have two aspects, static and dynamic. So, a model is considered as complete when both the aspects are fully covered.

Behavioral diagrams basically capture the dynamic aspect of a system. Dynamic aspect can be further described as the changing/moving parts of a system.

UML has the following five types of behavioral diagrams −

-   Use case diagram
-   Sequence diagram
-   Collaboration diagram
-   Statechart diagram
-   Activity diagram

### Use Case Diagram

Use case diagrams are a set of use cases, actors, and their relationships. They represent the use case view of a system.

A use case represents a particular functionality of a system. Hence, use case diagram is used to describe the relationships among the functionalities and their internal/external controllers. These controllers are known as **actors**.

### Sequence Diagram

A sequence diagram is an interaction diagram. From the name, it is clear that the diagram deals with some sequences, which are the sequence of messages flowing from one object to another.

Interaction among the components of a system is very important from implementation and execution perspective. Sequence diagram is used to visualize the sequence of calls in a system to perform a specific functionality.

### Collaboration Diagram

Collaboration diagram is another form of interaction diagram. It represents the structural organization of a system and the messages sent/received. Structural organization consists of objects and links.

The purpose of collaboration diagram is similar to sequence diagram. However, the specific purpose of collaboration diagram is to visualize the organization of objects and their interaction.

### Statechart Diagram

Any real-time system is expected to be reacted by some kind of internal/external events. These events are responsible for state change of the system.

Statechart diagram is used to represent the event driven state change of a system. It basically describes the state change of a class, interface, etc.

State chart diagram is used to visualize the reaction of a system by internal/external factors.

### Activity Diagram

Activity diagram describes the flow of control in a system. It consists of activities and links. The flow can be sequential, concurrent, or branched.

Activities are nothing but the functions of a system. Numbers of activity diagrams are prepared to capture the entire flow in a system.

Activity diagrams are used to visualize the flow of controls in a system. This is prepared to have an idea of how the system will work when executed.

**Note** − Dynamic nature of a system is very difficult to capture. UML has provided features to capture the dynamics of a system from different angles. Sequence diagrams and collaboration diagrams are isomorphic, hence they can be converted from one another without losing any information. This is also true for Statechart and activity diagram.