System design patterns are categorized into three types: Creational, structural, and Behavioral patterns. We explored different design patterns, including the Factory Method and Singleton patterns. 

The Factory Method pattern, while suitable for creating objects of related types without specifying their concrete classes, did not provide the level of flexibility and customization we needed for configuring `Account` and `TodoItem` instances. Additionally, the Singleton pattern, which ensures a class has only one instance and provides a global point of access to it, was not applicable to our scenario. The reason is, it would limit our ability to create multiple `TodoItem` instances with different configurations.

Other patterns within Structural Patterns and Behavioral Patterns seemed the next step for the scalability. So, after evaluating these patterns and their suitability for our application's architecture, we determined that the Builder pattern offered the best fit. Its ability to encapsulate the construction process and provide a flexible way for creating complex objects made it an ideal choice for constructing `TodoItem` instances with varying configurations. By adopting the Builder pattern, we ensure that our application remains scalable, maintainable, and adaptable to future changes and requirements.

## How are we using this pattern in our System? 
Here is how it is being used in the above UML Diagram:
1. **Building `Account` with `Password` and `User` Class**:
    In our system architecture, the `Account` entity comprises user credentials and personal information, which are represented by the `Password` and `User` classes, respectively. To streamline the creation of `Account` instances with varying configurations and to make each class responsible for small tasks, we employed the Builder pattern.
    
    The `Account` class serves as the primary builder for `Account` objects. It uses the construction process by utilizing methods to set the properties of the `Password` and `User` components directly within the `Account` class.
    
    By utilizing the Builder pattern in this context, we ensure that the creation of `Account` objects remains flexible and maintainable. The encapsulation of construction logic within the `Account` class and dividing the responsibilities across multiple other classes simplifies the instantiation process and promotes code readability.
    
2. **Building `TodoItem` with Different Configurations**:
    Within our task management module, the `TodoItem` class represents individual tasks with various attributes such as priority, status, and due date. To facilitate the creation of `TodoItem` instances with customizable configurations, we adopt the Builder pattern.
    
    The `TodoItem` class itself acts as the builder for `TodoItem` objects. It provides methods for setting the attributes of the `TodoItem` with `Todo`, `Priority`, `Status`, and `Due Date`, allowing clients to specify the desired configuration through method calls.
    
    By leveraging the Builder pattern for `TodoItem` creation, we ensure that the construction process remains clear and adaptable. The `TodoItem` class encapsulates the logic for building `TodoItem` objects. It enables clients to construct instances with ease while maintaining code's flexibility and maintainability.
