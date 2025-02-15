# OOPs-IAlsoKnowJava

A Java project demonstrating the four pillars of Object-Oriented Programming (OOP): **Inheritance, Encapsulation, Polymorphism, and Abstraction**. This project provides practical examples to highlight the application of OOP principles in real-world scenarios and best practices in Java programming and Object-Oriented Design.

---

## Key Concepts

### 📌 Inheritance
Inheritance allows a class to inherit properties and methods from another class using the `super()` keyword. It represents an **IS-A** relationship, where the child class is a type of the parent class.

**Types of Inheritance Demonstrated:**
- **Single-Level Inheritance**: A child class inherits directly from a parent class.
- **Multilevel Inheritance**: A class inherits from another derived class, creating a chain of inheritance.
- **Hierarchical Inheritance**: Multiple child classes inherit from a common parent class.
- **Hybrid Inheritance**: A combination of multilevel and hierarchical inheritance, creating a more complex structure.

**Advantages:**
- Promotes code reusability
- Reduces redundancy
- Enhances maintainability and scalability

### 📌 Encapsulation
Encapsulation is the concept of wrapping data (variables) and methods together into a single unit called a **class**. It restricts direct access to data and allows controlled access through public methods (getters and setters).

**Advantages:**
- Protects an object's data integrity
- Prevents unauthorized access and modification
- Enhances modularity and maintainability

### 📌 Polymorphism
Polymorphism allows objects to take on multiple forms by enabling a single interface to be used for different types.

**Types of Polymorphism Demonstrated:**

#### Compile-Time Polymorphism
- **Constructor Overloading & Chaining**: Defining multiple constructors with different parameters and reusing them via `this()` or `super()`.
- **Method Overloading**: Defining multiple methods with the same name but different parameters in the same class.

#### Runtime Polymorphism
- **Method Overriding**: A subclass redefines a method from its parent class to provide a specific implementation.
- **Upcasting**: Assigning a child class object to a parent class reference, enabling dynamic method dispatch.

---

## Project Structure

### 1) Inheritance
#### Single-Level Inheritance
A child class inherits directly from a parent class.
- **Loan.java** (Parent Class)  
  └── **PersonalLoan.java** (Child Class - extends Loan)

#### Hybrid Inheritance (Multilevel + Hierarchical)
A complex structure combining multilevel and hierarchical inheritance.
- **Product.java** (Parent Class)
  ├── **Shirt.java** (Child Class - extends Product)
  ├── **Laptop.java** (Child Class - extends Product)
      └── **Mobile.java** (Child Class - extends Laptop)

### 2) Encapsulation
#### User/UserDriver Class
- **Private Fields:** `name`, `id`
- **Getter/Setter Methods:**  
  - `getName()`, `setName(String name)`
  - `getId()`, `setId(int id)`

#### Laptop/LaptopDriver Class
- **Private Fields:** `name`, `storage`
- **Getter/Setter Methods:**  
  - `getName()`, `setName(String name)`
  - `getStorage()`, `setStorage(int storage)`

#### Vehicle/VehicleDriver Class
- **Private Fields:** `name`, `price`
- **Getter/Setter Methods:**  
  - `getName()`, `setName(String name)`
  - `getPrice()`, `setPrice(double price)`

### 3) Polymorphism
#### Compile-Time Polymorphism
- **Constructor Overloading & Chaining**
  - **Fruit.java**, **Weapon.java**, **Laptop.java** → Demonstrates constructor overloading and chaining.
- **Method Overloading**
  - **Fruit.java**, **Weapon.java**, **Laptop.java** → Implements method overloading with multiple parameter variations.

#### Runtime Polymorphism
- **Method Overriding**
  - **Fruit -> FruitMango**, **Laptop -> GamingLaptop**, **Weapon -> WeaponSword** → Override the `toString()` and `equals()` methods.
- **Upcasting**
  - **Fruit -> FruitMango**, **Laptop -> GamingLaptop**, **Weapon -> WeaponSword** → Demonstrates upcasting for dynamic method dispatch.