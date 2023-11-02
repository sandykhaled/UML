## UML (Unified Modeling Language)
1. UML is a way to use diagrams to understand System and database
2. UML can be divided into

    1. Structural Diagram
        1. composite structure diagram
        2. package diagram
        3. profile diagram
        4. class diagram
        5. component diagram
        6. object diagram
        7. deloyment diagram
           
    2. behavioural Diagram
        1. Activity Diagram
        2. State Machine Diagram
        3. Use Case Diagram
        4. Interaction Diagram
        5. Communication Diagram
        6. Timing Diagram
        7. Interaction overview Diagram
        8. Sequence Diagram
_____________________________________________

**1-Class Diagram**
1. Static Snapshot: A class diagram is like a frozen frame capturing the static structure of an application.
2. Components on Display: It showcases a collection of classes, interfaces, associations, collaborations, and constraints.
3. Blueprint for the Future: It forms the foundation for component and deployment diagrams.
   
   **Creating a Class Diagram**
   In the world of rectangles, here's how to craft a class diagram: <br/>
   **Part 1:** Class Name - The name starts with a capital letter. For abstract classes, it's written in an italic style. <br/>
   **Part 2:** Attributes - The characteristics of the class are listed here.  <br/>
   **Part 3:** Methods - The behaviors come to life with data types, and they sport special signs for access modifiers or class visibility:  <br/>
   1. {+} public 
   2. {-} private
   3. {#} protected
   4. {~} package local <br/>
   
    Method parameters are defined as: <br/>
   **method (in p1:boolean) :string** //for input <br/>
   **method (inout p1:boolean) :string**   //When it's input-output. <br/>
   **method (out p1:boolean) :string**    //Reserved for output. <br/>
   **Relationships between classes are the threads that weave the fabric of your application:**

   1. **Association** - A connection between classes.
   2. **Inheritance** (Generalization) - The parent-child bond.
   3. **Realization** - Clarifying the relationship between interfaces and their implementers.
   4. **Dependency** - When one class relies on another.
   5. **Aggregation** - One class comprises multiple classes. Removing it doesn't affect the others.
   6. **Composition** - A special case of aggregation. The aggregator class holds the power to destroy.
   Writing a class diagram is like crafting a blueprint for your software masterpiece, where each element has its place and purpose.

   ______________________________

   **2-Component Diagram**
   
A component diagram is a type of diagram used in UML (Unified Modeling Language) to model the physical aspects of a system. It visualizes the components of a system, which are physical elements such as executables, libraries, files, documents, and more. This diagram helps describe the organization and relationships between these components.

   **Where To Use component Diagram**
   1.**Modeling Components:** <br/>
     Component diagrams are used to model the components of a system, making it easier to understand the structure of the system.
   
   2. **Modeling Database Schema:** <br/>
     They can be used to model the database schema, showing how components interact with the database.

   3. **Modeling Executables:** <br/>
       Component diagrams can represent the executables and applications in a system, providing insight into their relationships.
      
   5. **Modeling Source Code:** <br/>
       They can also be used to model the system's source code, illustrating how different code components work together.
1. **Node (Component):** <br/>
   Each node in the component diagram represents a component. A component can consist of one or more classes, and it is typically depicted as a rectangle.
   
2. **Edge (Relationship):** <br/>
   Relationships between components are represented by edges. There are two types of edges: dashed and solid, which indicate different types of 
   relationships between components.
      
3. **Lollipop:** <br/>
    A circle symbol in a component diagram typically represents an interface, indicating that the component provides or implements certain interfaces.
   
4. **Required Interface:** <br/>
     A semicircle symbol is used to represent a required interface, signifying that a component relies on or requires a specific interface.
   
5. **Square (Port):** <br/>
    A square symbol may be used to denote a port within a component, allowing for connections to other components or external entities.
   
6. **Constraint:** <br/>
    Constraints are expressed as text in natural language and provide additional information about the components or relationships in the diagram.
   <br/>
By using these symbols and notations in a component diagram, you can create visual representations of the physical structure of a system, making it easier to understand and communicate the organization and relationships of its components. This is particularly valuable in the design and documentation of software systems and other complex systems.
   
