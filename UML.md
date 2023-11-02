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


**Class Diagram**
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
    Method parameters are defined as:
   **method (in p1:boolean) :string** //for input
   **method (inout p1:boolean) :string**   //When it's input-output.
   **method (out p1:boolean) :string**    //Reserved for output.
   **Relationships between classes are the threads that weave the fabric of your application:**
1. ***Association** - A connection between classes.
2. **Inheritance** (Generalization) - The parent-child bond.
3. **Realization** - Clarifying the relationship between interfaces and their implementers.
4. **Dependency** - When one class relies on another.
5. **Aggregation** - One class comprises multiple classes. Removing it doesn't affect the others.
6. **Composition** - A special case of aggregation. The aggregator class holds the power to destroy.
Writing a class diagram is like crafting a blueprint for your software masterpiece, where each element has its place and purpose.

   
   أخ 
        
