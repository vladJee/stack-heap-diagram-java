# Stack-Heap Diagram: Java Memory Model

This repository contains a PlantUML diagram that visualizes how stack and heap memory are used during the execution of a Java program.

---

The diagram illustrates the behavior of a Java program, specifically the interaction between stack and heap memory during the execution of the `main`, `fill`, and `shrink` methods.

- **Stack Memory** contains local primitive variables and references to objects created within the methods.
- **Heap Memory** contains the objects referenced by the local variables from the stack.

### Method Execution Order:
- First, the `main` method is called, creating variables: `name`, `list`, and `times`.
- Next, the `fill` method is invoked, using the passed arguments and creating additional local variables.
- The `shrink` method is then called from within `fill`, creating its own local variables.

### Links:
- All references on the stack correctly point to their corresponding objects in the heap..


