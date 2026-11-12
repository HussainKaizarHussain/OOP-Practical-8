# OOP-Practical-8: Singleton Design Pattern

## Purpose & Aim
- **Aim**: To practise applying a common object-creation design pattern instead of creating objects without a clear structure.
- **Question**: Implement either the Singleton or Factory design pattern in C++ and discuss its use case and trade-offs.

---

## What to Do
- Choose one pattern: Singleton or Factory. State why it fits your example.
- For Singleton, create a class that controls access to a single instance.
- Demonstrate the pattern in a small program, such as application settings (Singleton) or shape/vehicle creation (Factory).
- Show the pattern working with at least two calls or requested object types.
- Write a short note covering one benefit and one trade-off, such as global access and testing difficulty for Singleton.

---

## Use Case & Trade-offs (Singleton)
- **Use Case**: Managing shared application configuration settings or a global database connection pool where only one instance should exist across the entire program.
- **Benefit**: Controlled access to a sole instance and global point of access.
- **Trade-off**: Introduces global state, which can make unit testing more difficult due to tight coupling.
