
# Class diagrm
[UML - Class Diagram - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_class_diagram.htm)

## Purpose of Class Diagrams

The purpose of class diagram is to model the static view of an application. Class diagrams are the only diagrams which can be directly mapped with object-oriented languages and thus widely used at the time of construction.

The purpose of the class diagram can be summarized as −

-   Analysis and design of the static view of an application.
    
-   Describe responsibilities of a system.
    
-   Base for component and deployment diagrams.
    
-   Forward and reverse engineering.
    

## How to Draw a Class Diagram?

Class diagrams have a lot of properties to consider while drawing but here the diagram will be considered from a top level view.

Class diagram is basically a graphical representation of the static view of the system and represents different aspects of the application. A collection of class diagrams represent the whole system.

The following points should be remembered while drawing a class diagram −

-   The name of the class diagram should be meaningful to describe the aspect of the system.
    
-   Each element and their relationships should be identified in advance.
    
-   Responsibility (attributes and methods) of each class should be clearly identified
    
-   For each class, minimum number of properties should be specified, as unnecessary properties will make the diagram complicated.
    
-   Use notes whenever required to describe some aspect of the diagram. At the end of the drawing it should be understandable to the developer/coder.
    
-   Finally, before making the final version, the diagram should be drawn on plain paper and reworked as many times as possible to make it correct.
    

The following diagram is an example of an Order System of an application. It describes a particular aspect of the entire application.

-   First of all, Order and Customer are identified as the two elements of the system. They have a one-to-many relationship because a customer can have multiple orders.
    
-   Order class is an abstract class and it has two concrete classes (inheritance relationship) SpecialOrder and NormalOrder.
    
-   The two inherited classes have all the properties as the Order class. In addition, they have additional functions like dispatch () and receive ().
    

The following class diagram has been drawn considering all the points mentioned above.

![UML Class Diagram](https://www.tutorialspoint.com/uml/images/uml_class_diagram.jpg)

## Where to Use Class Diagrams?

In a nutshell it can be said, class diagrams are used for −

-   Describing the static view of the system.
    
-   Showing the collaboration among the elements of the static view.
    
-   Describing the functionalities performed by the system.
    
-   Construction of software applications using object oriented languages.

# Object Diagrams
[UML - Object Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_object_diagram.htm)

 Object diagrams are used to render a set of objects and their relationships as an instance.
 
 ## Purpose of Object Diagrams
 
 The purpose of a diagram should be understood clearly to implement it practically. The purposes of object diagrams are similar to class diagrams.
 
 The difference is that a class diagram represents an abstract model consisting of classes and their relationships. However, an object diagram represents an instance at a particular moment, which is concrete in nature.
 
 It means the object diagram is closer to the actual system behavior. The purpose is to capture the static view of a system at a particular moment.
 
 The purpose of the object diagram can be summarized as −
 
 -   Forward and reverse engineering.
     
 -   Object relationships of a system
     
 -   Static view of an interaction.
     
 -   Understand object behaviour and their relationship from practical perspective
     
 
 ## How to Draw an Object Diagram?
 
 We have already discussed that an object diagram is an instance of a class diagram. It implies that an object diagram consists of instances of things used in a class diagram.
 
 So both diagrams are made of same basic elements but in different form. In class diagram elements are in abstract form to represent the blue print and in object diagram the elements are in concrete form to represent the real world object.
 
 To capture a particular system, numbers of class diagrams are limited. However, if we consider object diagrams then we can have unlimited number of instances, which are unique in nature. Only those instances are considered, which have an impact on the system.
 
 From the above discussion, it is clear that a single object diagram cannot capture all the necessary instances or rather cannot specify all the objects of a system. Hence, the solution is −
 
 -   First, analyze the system and decide which instances have important data and association.
     
 -   Second, consider only those instances, which will cover the functionality.
     
 -   Third, make some optimization as the number of instances are unlimited.
     
 
 Before drawing an object diagram, the following things should be remembered and understood clearly −
 
 -   Object diagrams consist of objects.
     
 -   The link in object diagram is used to connect objects.
     
 -   Objects and links are the two elements used to construct an object diagram.
     
 
 After this, the following things are to be decided before starting the construction of the diagram −
 
 -   The object diagram should have a meaningful name to indicate its purpose.
     
 -   The most important elements are to be identified.
     
 -   The association among objects should be clarified.
     
 -   Values of different elements need to be captured to include in the object diagram.
     
 -   Add proper notes at points where more clarity is required.
     
 
 The following diagram is an example of an object diagram. It represents the Order management system which we have discussed in the chapter Class Diagram. The following diagram is an instance of the system at a particular time of purchase. It has the following objects.
 
 -   Customer
     
 -   Order
     
 -   SpecialOrder
     
 -   NormalOrder
     
 
 Now the customer object (C) is associated with three order objects (O1, O2, and O3). These order objects are associated with special order and normal order objects (S1, S2, and N1). The customer has the following three orders with different numbers (12, 32 and 40) for the particular time considered.
 
 The customer can increase the number of orders in future and in that scenario the object diagram will reflect that. If order, special order, and normal order objects are observed then you will find that they have some values.
 
 For orders, the values are 12, 32, and 40 which implies that the objects have these values for a particular moment (here the particular time when the purchase is made is considered as the moment) when the instance is captured
 
 The same is true for special order and normal order objects which have number of orders as 20, 30, and 60. If a different time of purchase is considered, then these values will change accordingly.
 
 The following object diagram has been drawn considering all the points mentioned above
 
 ![UML Object Diagram](https://www.tutorialspoint.com/uml/images/uml_object_diagram.jpg)
 
 ## Where to Use Object Diagrams?
 
 Object diagrams can be imagined as the snapshot of a running system at a particular moment. Let us consider an example of a running train
 
 Now, if you take a snap of the running train then you will find a static picture of it having the following −
 
 -   A particular state which is running.
     
 -   A particular number of passengers. which will change if the snap is taken in a different time
     
 
 Here, we can imagine the snap of the running train is an object having the above values. And this is true for any real-life simple or complex system.
 
 In a nutshell, it can be said that object diagrams are used for −
 
 -   Making the prototype of a system.
     
 -   Reverse engineering.
     
 -   Modeling complex data structures.
     
 -   Understanding the system from practical perspective.

 # Component Diagrams
 [UML - Component Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_component_diagram.htm)

 Component diagrams are different in terms of nature and behavior. Component diagrams are used to model the physical aspects of a system. Now the question is, what are these physical aspects? Physical aspects are the elements such as executables, libraries, files, documents, etc. which reside in a node.
 
 Component diagrams are used to visualize the organization and relationships among components in a system. These diagrams are also used to make executable systems.
 
 ## Purpose of Component Diagrams
 
 Component diagram is a special kind of diagram in UML. The purpose is also different from all other diagrams discussed so far. It does not describe the functionality of the system but it describes the components used to make those functionalities.
 
 Thus from that point of view, component diagrams are used to visualize the physical components in a system. These components are libraries, packages, files, etc.
 
 Component diagrams can also be described as a static implementation view of a system. Static implementation represents the organization of the components at a particular moment.
 
 A single component diagram cannot represent the entire system but a collection of diagrams is used to represent the whole.
 
 The purpose of the component diagram can be summarized as −
 
 -   Visualize the components of a system.
     
 -   Construct executables by using forward and reverse engineering.
     
 -   Describe the organization and relationships of the components.
     
 
 ## How to Draw a Component Diagram?
 
 Component diagrams are used to describe the physical artifacts of a system. This artifact includes files, executables, libraries, etc
 
 The purpose of this diagram is different. Component diagrams are used during the implementation phase of an application. However, it is prepared well in advance to visualize the implementation details.
 
 Initially, the system is designed using different UML diagrams and then when the artifacts are ready, component diagrams are used to get an idea of the implementation.
 
 This diagram is very important as without it the application cannot be implemented efficiently. A well-prepared component diagram is also important for other aspects such as application performance, maintenance, etc.
 
 Before drawing a component diagram, the following artifacts are to be identified clearly −
 
 -   Files used in the system.
     
 -   Libraries and other artifacts relevant to the application.
     
 -   Relationships among the artifacts.
     
 
 After identifying the artifacts, the following points need to be kept in mind.
 
 -   Use a meaningful name to identify the component for which the diagram is to be drawn.
     
 -   Prepare a mental layout before producing the using tools.
     
 -   Use notes for clarifying important points.
     
 
 Following is a component diagram for order management system. Here, the artifacts are files. The diagram shows the files in the application and their relationships. In actual, the component diagram also contains dlls, libraries, folders, etc.
 
 In the following diagram, four files are identified and their relationships are produced. Component diagram cannot be matched directly with other UML diagrams discussed so far as it is drawn for completely different purpose.
 
 The following component diagram has been drawn considering all the points mentioned above.
 
 ![UML Component Diagram](https://www.tutorialspoint.com/uml/images/uml_component_diagram.jpg)
 
 ## Where to Use Component Diagrams?
 
 We have already described that component diagrams are used to visualize the static implementation view of a system. Component diagrams are special type of UML diagrams used for different purposes.
 
 These diagrams show the physical components of a system. To clarify it, we can say that component diagrams describe the organization of the components in a system.
 
 Organization can be further described as the location of the components in a system. These components are organized in a special way to meet the system requirements.
 
 As we have already discussed, those components are libraries, files, executables, etc. Before implementing the application, these components are to be organized. This component organization is also designed separately as a part of project execution.
 
 Component diagrams are very important from implementation perspective. Thus, the implementation team of an application should  have a proper knowledge of the component details
 
 Component diagrams can be used to −
 
 -   Model the components of a system.
     
 -   Model the database schema.
     
 -   Model the executables of an application.
     
 -   Model the system's source code.

# Deployment Diagrams
[UML - Deployment Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_deployment_diagram.htm)

 Deployment diagrams are used to visualize the topology of the physical components of a system, where the software components are deployed.
 
 Deployment diagrams are used to describe the static deployment view of a system. Deployment diagrams consist of nodes and their relationships.
 
 ## Purpose of Deployment Diagrams
 
 The term Deployment itself describes the purpose of the diagram. Deployment diagrams are used for describing the hardware components, where software components are deployed. Component diagrams and deployment diagrams are closely related.
 
 Component diagrams are used to describe the components and deployment diagrams shows how they are deployed in hardware.
 
 UML is mainly designed to focus on the software artifacts of a system. However, these two diagrams are special diagrams used to focus on software and hardware components.
 
 Most of the UML diagrams are used to handle logical components but deployment diagrams are made to focus on the hardware topology of a system. Deployment diagrams are used by the system engineers.
 
 The purpose of deployment diagrams can be described as −
 
 -   Visualize the hardware topology of a system.
     
 -   Describe the hardware components used to deploy software components.
     
 -   Describe the runtime processing nodes.
     
 
 ## How to Draw a Deployment Diagram?
 
 Deployment diagram represents the deployment view of a system. It is related to the component diagram because the components are deployed using the deployment diagrams. A deployment diagram consists of nodes. Nodes are nothing but physical hardware used to deploy the application.
 
 Deployment diagrams are useful for system engineers. An efficient deployment diagram is very important as it controls the following parameters −
 
 -   Performance
     
 -   Scalability
     
 -   Maintainability
     
 -   Portability
     
 
 Before drawing a deployment diagram, the following artifacts should be identified −
 
 -   Nodes
     
 -   Relationships among nodes
     
 
 Following is a sample deployment diagram to provide an idea of the deployment view of order management system. Here, we have shown nodes as −
 
 -   Monitor
     
 -   Modem
     
 -   Caching server
     
 -   Server
     
 
 The application is assumed to be a web-based application, which is deployed in a clustered environment using server 1, server 2, and server 3. The user connects to the application using the Internet. The control flows from the caching server to the clustered environment.
 
 The following deployment diagram has been drawn considering all the points mentioned above.
 
 ![UML Deployment Diagram](https://www.tutorialspoint.com/uml/images/uml_deployment_diagram.jpg)
 
 ## Where to Use Deployment Diagrams?
 
 Deployment diagrams are mainly used by system engineers. These diagrams are used to describe the physical components (hardware), their distribution, and association.
 
 Deployment diagrams can be visualized as the hardware components/nodes on which the software components reside.
 
 Software applications are developed to model complex business processes. Efficient software applications are not sufficient to meet the business requirements. Business requirements can be described as the need to support the increasing number of users, quick response time, etc.
 
 To meet these types of requirements, hardware components should be designed efficiently and in a cost-effective way.
 
 Now-a-days software applications are very complex in nature. Software applications can be standalone, web-based, distributed, mainframe-based and many more. Hence, it is very important to design the hardware components efficiently.
 
 Deployment diagrams can be used −
 
 -   To model the hardware topology of a system.
     
 -   To model the embedded system.
     
 -   To model the hardware details for a client/server system.
     
 -   To model the hardware details of a distributed application.
     
 -   For Forward and Reverse engineering.

# Use Case Diagrams
[UML - Use Case Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_use_case_diagram.htm)

 To model a system, the most important aspect is to capture the dynamic behavior. Dynamic behavior means the behavior of the system when it is running/operating.
 
 Only static behavior is not sufficient to model a system rather dynamic behavior is more important than static behavior. In UML, there are five diagrams available to model the dynamic nature and use case diagram is one of them. Now as we have to discuss that the use case diagram is dynamic in nature, there should be some internal or external factors for making the interaction.
 
 These internal and external agents are known as actors. Use case diagrams consists of actors, use cases and their relationships. The diagram is used to model the system/subsystem of an application. A single use case diagram captures a particular functionality of a system.
 
 Hence to model the entire system, a number of use case diagrams are used.
 
 ## Purpose of Use Case Diagrams
 
 The purpose of use case diagram is to capture the dynamic aspect of a system. However, this definition is too generic to describe the purpose, as other four diagrams (activity, sequence, collaboration, and Statechart) also have the same purpose. We will look into some specific purpose, which will distinguish it from other four diagrams.
 
 Use case diagrams are used to gather the requirements of a system including internal and external influences. These requirements are mostly design requirements. Hence, when a system is analyzed to gather its functionalities, use cases are prepared and actors are identified.
 
 When the initial task is complete, use case diagrams are modelled to present the outside view.
 
 In brief, the purposes of use case diagrams can be said to be as follows −
 
 -   Used to gather the requirements of a system.
     
 -   Used to get an outside view of a system.
     
 -   Identify the external and internal factors influencing the system.
     
 -   Show the interaction among the requirements are actors.
     
 
 ## How to Draw a Use Case Diagram?
 
 Use case diagrams are considered for high level requirement analysis of a system. When the requirements of a system are analyzed, the functionalities are captured in use cases.
 
 We can say that use cases are nothing but the system functionalities written in an organized manner. The second thing which is relevant to use cases are the actors. Actors can be defined as something that interacts with the system.
 
 Actors can be a human user, some internal applications, or may be some external applications. When we are planning to draw a use case diagram, we should have the following items identified.
 
 -   Functionalities to be represented as use case
     
 -   Actors
     
 -   Relationships among the use cases and actors.
     
 
 Use case diagrams are drawn to capture the functional requirements of a system. After identifying the above items, we have to use the following guidelines to draw an efficient use case diagram
 
 -   The name of a use case is very important. The name should be chosen in such a way so that it can identify the functionalities performed.
     
 -   Give a suitable name for actors.
     
 -   Show relationships and dependencies clearly in the diagram.
     
 -   Do not try to include all types of relationships, as the main purpose of the diagram is to identify the requirements.
     
 -   Use notes whenever required to clarify some important points.
     
 
 Following is a sample use case diagram representing the order management system. Hence, if we look into the diagram then we will find three use cases **(Order, SpecialOrder, and NormalOrder)** and one actor which is the customer.
 
 The SpecialOrder and NormalOrder use cases are extended from _Order_ use case. Hence, they have extended relationship. Another important point is to identify the system boundary, which is shown in the picture. The actor Customer lies outside the system as it is an external user of the system.
 
 ![UML Use Case Diagram](https://www.tutorialspoint.com/uml/images/uml_use_case_diagram.jpg)
 
 ## Where to Use a Use Case Diagram?
 
 As we have already discussed there are five diagrams in UML to model the dynamic view of a system. Now each and every model has some specific purpose to use. Actually these specific purposes are different angles of a running system.
 
 To understand the dynamics of a system, we need to use different types of diagrams. Use case diagram is one of them and its specific purpose is to gather system requirements and actors.
 
 Use case diagrams specify the events of a system and their flows. But use case diagram never describes how they are implemented. Use case diagram can be imagined as a black box where only the input, output, and the function of the black box is known.
 
 These diagrams are used at a very high level of design. This high level design is refined again and again to get a complete and practical picture of the system. A well-structured use case also describes the pre-condition, post condition, and exceptions. These extra elements are used to make test cases when performing the testing.
 
 Although use case is not a good candidate for forward and reverse engineering, still they are used in a slightly different way to make forward and reverse engineering. The same is true for reverse engineering. Use case diagram is used differently to make it suitable for reverse engineering.
 
 In forward engineering, use case diagrams are used to make test cases and in reverse engineering use cases are used to prepare the requirement details from the existing application.
 
 Use case diagrams can be used for −
 
 -   Requirement analysis and high level design.
     
 -   Model the context of a system.
     
 -   Reverse engineering.
     
 -   Forward engineering.

# Interaction Diagrams
[UML - Interaction Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_interaction_diagram.htm)

 From the term Interaction, it is clear that the diagram is used to describe some type of interactions among the different elements in the model. This interaction is a part of dynamic behavior of the system.
 
 This interactive behavior is represented in UML by two diagrams known as **Sequence diagram** and **Collaboration diagram**. The basic purpose of both the diagrams are similar.
 
 Sequence diagram emphasizes on time sequence of messages and collaboration diagram emphasizes on the structural organization of the objects that send and receive messages.
 
 ## Purpose of Interaction Diagrams
 
 The purpose of interaction diagrams is to visualize the interactive behavior of the system. Visualizing the interaction is a difficult task. Hence, the solution is to use different types of models to capture the different aspects of the interaction.
 
 Sequence and collaboration diagrams are used to capture the dynamic nature but from a different angle.
 
 The purpose of interaction diagram is −
 
 -   To capture the dynamic behaviour of a system.
     
 -   To describe the message flow in the system.
     
 -   To describe the structural organization of the objects.
     
 -   To describe the interaction among objects.
     
 
 ## How to Draw an Interaction Diagram?
 
 As we have already discussed, the purpose of interaction diagrams is to capture the dynamic aspect of a system. So to capture the dynamic aspect, we need to understand what a dynamic aspect is and how it is visualized. Dynamic aspect can be defined as the snapshot of the running system at a particular moment
 
 We have two types of interaction diagrams in UML. One is the sequence diagram and the other is the collaboration diagram. The sequence diagram captures the time sequence of the message flow from one object to another and the collaboration diagram describes the organization of objects in a system taking part in the message flow.
 
 Following things are to be identified clearly before drawing the interaction diagram
 
 -   Objects taking part in the interaction.
     
 -   Message flows among the objects.
     
 -   The sequence in which the messages are flowing.
     
 -   Object organization.
     
 
 Following are two interaction diagrams modeling the order management system. The first diagram is a sequence diagram and the second is a collaboration diagram
 
 ### The Sequence Diagram
 
 The sequence diagram has four objects (Customer, Order, SpecialOrder and NormalOrder).
 
 The following diagram shows the message sequence for _SpecialOrder_ object and the same can be used in case of _NormalOrder_ object. It is important to understand the time sequence of message flows. The message flow is nothing but a method call of an object.
 
 The first call is _sendOrder ()_ which is a method of _Order object_. The next call is _confirm ()_ which is a method of _SpecialOrder_ object and the last call is _Dispatch ()_ which is a method of _SpecialOrder_ object. The following diagram mainly describes the method calls from one object to another, and this is also the actual scenario when the system is running.
 
 ![UML Sequence Diagram](https://www.tutorialspoint.com/uml/images/uml_sequence_diagram.jpg)
 
 ### The Collaboration Diagram
 
 The second interaction diagram is the collaboration diagram. It shows the object organization as seen in the following diagram. In the collaboration diagram, the method call sequence is indicated by some numbering technique. The number indicates how the methods are called one after another. We have taken the same order management system to describe the collaboration diagram.
 
 Method calls are similar to that of a sequence diagram. However, difference being the sequence diagram does not describe the object organization, whereas the collaboration diagram shows the object organization.
 
 To choose between these two diagrams, emphasis is placed on the type of requirement. If the time sequence is important, then the sequence diagram is used. If organization is required, then collaboration diagram is used.
 
 ![UML Collaboration Diagram](https://www.tutorialspoint.com/uml/images/uml_collaboration_diagram.jpg)
 
 ## Where to Use Interaction Diagrams?
 
 We have already discussed that interaction diagrams are used to describe the dynamic nature of a system. Now, we will look into the practical scenarios where these diagrams are used. To understand the practical application, we need to understand the basic nature of sequence and collaboration diagram.
 
 The main purpose of both the diagrams are similar as they are used to capture the dynamic behavior of a system. However, the specific purpose is more important to clarify and understand.
 
 Sequence diagrams are used to capture the order of messages flowing from one object to another. Collaboration diagrams are used to describe the structural organization of the objects taking part in the interaction. A single diagram is not sufficient to describe the dynamic aspect of an entire system, so a set of diagrams are used to capture it as a whole.
 
 Interaction diagrams are used when we want to understand the message flow and the structural organization. Message flow means the sequence of control flow from one object to another. Structural organization means the visual organization of the elements in a system.
 
 Interaction diagrams can be used −
 
 -   To model the flow of control by time sequence.
     
 -   To model the flow of control by structural organizations.
     
 -   For forward engineering.
     
 -   For reverse engineering.

# Statechart Diagrams
[UML - Statechart Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_statechart_diagram.htm)

 The name of the diagram itself clarifies the purpose of the diagram and other details. It describes different states of a component in a system. The states are specific to a component/object of a system.
 
 A Statechart diagram describes a state machine. State machine can be defined as a machine which defines different states of an object and these states are controlled by external or internal events.
 
 Activity diagram explained in the next chapter, is a special kind of a Statechart diagram. As Statechart diagram defines the states, it is used to model the lifetime of an object.
 
 ## Purpose of Statechart Diagrams
 
 Statechart diagram is one of the five UML diagrams used to model the dynamic nature of a system. They define different states of an object during its lifetime and these states are changed by events. Statechart diagrams are useful to model the reactive systems. Reactive systems can be defined as a system that responds to external or internal events.
 
 Statechart diagram describes the flow of control from one state to another state. States are defined as a condition in which an object exists and it changes when some event is triggered. The most important purpose of Statechart diagram is to model lifetime of an object from creation to termination.
 
 Statechart diagrams are also used for forward and reverse engineering of a system. However, the main purpose is to model the reactive system.
 
 Following are the main purposes of using Statechart diagrams −
 
 -   To model the dynamic aspect of a system.
     
 -   To model the life time of a reactive system.
     
 -   To describe different states of an object during its life time.
     
 -   Define a state machine to model the states of an object.
     
 
 ## How to Draw a Statechart Diagram?
 
 Statechart diagram is used to describe the states of different objects in its life cycle. Emphasis is placed on the state changes upon some internal or external events. These states of objects are important to analyze and implement them accurately.
 
 Statechart diagrams are very important for describing the states. States can be identified as the condition of objects when a particular event occurs.
 
 Before drawing a Statechart diagram we should clarify the following points −
 
 -   Identify the important objects to be analyzed.
     
 -   Identify the states.
     
 -   Identify the events.
     
 
 Following is an example of a Statechart diagram where the state of Order object is analyzed
 
 The first state is an idle state from where the process starts. The next states are arrived for events like send request, confirm request, and dispatch order. These events are responsible for the state changes of order object.
 
 During the life cycle of an object (here order object) it goes through the following states and there may be some abnormal exits. This abnormal exit may occur due to some problem in the system. When the entire life cycle is complete, it is considered as a complete transaction as shown in the following figure. The initial and final state of an object is also shown in the following figure.
 
 ![UML Statechart Diagram](https://www.tutorialspoint.com/uml/images/uml_statechart_diagram.jpg)
 
 ## Where to Use Statechart Diagrams?
 
 From the above discussion, we can define the practical applications of a Statechart diagram. Statechart diagrams are used to model the dynamic aspect of a system like other four diagrams discussed in this tutorial. However, it has some distinguishing characteristics for modeling the dynamic nature.
 
 Statechart diagram defines the states of a component and these state changes are dynamic in nature. Its specific purpose is to define the state changes triggered by events. Events are internal or external factors influencing the system.
 
 Statechart diagrams are used to model the states and also the events operating on the system. When implementing a system, it is very important to clarify different states of an object during its life time and Statechart diagrams are used for this purpose. When these states and events are identified, they are used to model it and these models are used during the implementation of the system.
 
 If we look into the practical implementation of Statechart diagram, then it is mainly used to analyze the object states influenced by events. This analysis is helpful to understand the system behavior during its execution.
 
 The main usage can be described as −
 
 -   To model the object states of a system.
     
 -   To model the reactive system. Reactive system consists of reactive objects.
     
 -   To identify the events responsible for state changes.
     
 -   Forward and reverse engineering.

# Activity Diagrams
[UML - Activity Diagrams - Tutorialspoint](https://www.tutorialspoint.com/uml/uml_activity_diagram.htm)

 Activity diagram is another important diagram in UML to describe the dynamic aspects of the system.
 
 Activity diagram is basically a flowchart to represent the flow from one activity to another activity. The activity can be described as an operation of the system.
 
 The control flow is drawn from one operation to another. This flow can be sequential, branched, or concurrent. Activity diagrams deal with all type of flow control by using different elements such as fork, join, etc
 
 ## Purpose of Activity Diagrams
 
 The basic purposes of activity diagrams is similar to other four diagrams. It captures the dynamic behavior of the system. Other four diagrams are used to show the message flow from one object to another but activity diagram is used to show message flow from one activity to another.
 
 Activity is a particular operation of the system. Activity diagrams are not only used for visualizing the dynamic nature of a system, but they are also used to construct the executable system by using forward and reverse engineering techniques. The only missing thing in the activity diagram is the message part.
 
 It does not show any message flow from one activity to another. Activity diagram is sometimes considered as the flowchart. Although the diagrams look like a flowchart, they are not. It shows different flows such as parallel, branched, concurrent, and single.
 
 The purpose of an activity diagram can be described as −
 
 -   Draw the activity flow of a system.
     
 -   Describe the sequence from one activity to another.
     
 -   Describe the parallel, branched and concurrent flow of the system.
     
 
 ## How to Draw an Activity Diagram?
 
 Activity diagrams are mainly used as a flowchart that consists of activities performed by the system. Activity diagrams are not exactly flowcharts as they have some additional capabilities. These additional capabilities include branching, parallel flow, swimlane, etc.
 
 Before drawing an activity diagram, we must have a clear understanding about the elements used in activity diagram. The main element of an activity diagram is the activity itself. An activity is a function performed by the system. After identifying the activities, we need to understand how they are associated with constraints and conditions.
 
 Before drawing an activity diagram, we should identify the following elements −
 
 -   Activities
     
 -   Association
     
 -   Conditions
     
 -   Constraints
     
 
 Once the above-mentioned parameters are identified, we need to make a mental layout of the entire flow. This mental layout is then transformed into an activity diagram.
 
 Following is an example of an activity diagram for order management system. In the diagram, four activities are identified which are associated with conditions. One important point should be clearly understood that an activity diagram cannot be exactly matched with the code. The activity diagram is made to understand the flow of activities and is mainly used by the business users
 
 Following diagram is drawn with the four main activities −
 
 -   Send order by the customer
     
 -   Receipt of the order
     
 -   Confirm the order
     
 -   Dispatch the order
     
 
 After receiving the order request, condition checks are performed to check if it is normal or special order. After the type of order is identified, dispatch activity is performed and that is marked as the termination of the process.
 
 ![UML Activity Diagram](https://www.tutorialspoint.com/uml/images/uml_activity_diagram.jpg)
 
 ## Where to Use Activity Diagrams?
 
 The basic usage of activity diagram is similar to other four UML diagrams. The specific usage is to model the control flow from one activity to another. This control flow does not include messages.
 
 Activity diagram is suitable for modeling the activity flow of the system. An application can have multiple systems. Activity diagram also captures these systems and describes the flow from one system to another. This specific usage is not available in other diagrams. These systems can be database, external queues, or any other system.
 
 We will now look into the practical applications of the activity diagram. From the above discussion, it is clear that an activity diagram is drawn from a very high level. So it gives high level view of a system. This high level view is mainly for business users or any other person who is not a technical person.
 
 This diagram is used to model the activities which are nothing but business requirements. The diagram has more impact on business understanding rather than on implementation details.
 
 Activity diagram can be used for −
 
 -   Modeling work flow by using activities.
     
 -   Modeling business requirements.
     
 -   High level understanding of the system's functionalities.
     
 -   Investigating business requirements at a later stage.

