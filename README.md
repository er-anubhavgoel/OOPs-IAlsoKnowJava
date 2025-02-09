# OOPs-IAlsoKnowJava 

A Java project demonstrating the 4 pillars of **Object-Oriented Programming (OOP):** *Inheritance*, *Encapsulation*, *Polymorphism*, and *Abstraction*. This project showcases practical examples to highlight the application of OOP principles in real-world scenarios and best practices in Java programming and Object-Oriented Design.

---

## Key Concepts:
- **Inheritance**: Inheritance allows a class to inherit properties and methods from another class using the super() keyword. It represents an IS-A relationship, where the child class is a type of the parent class.
    ***Advantage***: Inheritance promotes code reuse, reduces redundancy, and makes it easier to maintain and modify code.

- **Encapsulation**: Encapsulation is the concept of wrapping data (variables) and methods together into a single unit called a class. It allows data to be hidden from outside access and can only be accessed through public methods (getters and setters).
    ***Advantage***: Encapsulation protects an object's data integrity by restricting unauthorized access and modification.

## Project Structure:

### 1) Inheritance:
- **single_level_inheritance**: A child class inherits directly from a parent class.
  ```
  Loan.java (Parent Class)
  └── PersonalLoan.java (Child Class - extends Loan)
  ```

- **hybrid_inheritance**: Combines multilevel and hierarchical inheritance.
  ```
  Product.java (Parent Class)
  ├── Shirt.java (Child Class - extends Product)
  ├── Laptop.java (Child Class - extends Product)
      └── Mobile.java (Child Class - extends Laptop)
  ```

### 2) Encapsulation:
- **User/UserDriver Class**:
  - Private fields: `name`, `id`
  - Getter/Setter methods:  
    - `getName()`, `setName(String name)`  
    - `getId()`, `setId(int id)`

- **Laptop/LaptopDriver Class**:
  - Private fields: `name`, `storage`
  - Getter/Setter methods:  
    - `getName()`, `setName(String name)`  
    - `getStorage()`, `setStorage(int storage)`

- **Vehicle/VehicleDriver Class**:
  - Private fields: `name`, `price`
  - Getter/Setter methods:  
    - `getName()`, `setName(String name)`  
    - `getPrice()`, `setPrice(double price)`
