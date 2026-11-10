# Object-Oriented Programming in Java

A portfolio of focused Java exercises covering domain modeling, inheritance, geometry, serialization, and client/server interaction. Each directory is a self-contained learning project with its own entry point.

## Project map

| Directory | Concepts and implementation |
| --- | --- |
| `banking/` | `Person`, `Account`, and `Bank` models with the `mainPackage.BDBank` driver |
| `employee/` | Commission-based compensation and inheritance through `CommissionEmployee` and `BasePlusCommissionEmployee` |
| `library/` | Author, book, and library relationships with a console driver |
| `circle/` | A `Circle2D` model and a demonstration program |
| `mPrime/` | A numerical exercise organized around an `MPrime` class |
| `AccountSerialization/` | Account objects, file storage, and an operator layer |
| `bankClient/` | A separate client program with an `Operator` abstraction |

Root-level `One.java` and `Two.java` provide additional standalone Java exercises.

## Running an example

Use a JDK and compile each exercise independently. For the library example, run from the repository root:

```bash
javac -d /tmp/oop-library library/*.java
java -cp /tmp/oop-library MainClass
```

Match the runtime class name to the package declaration in the selected source. The serialization and client projects include IDE project metadata; import their directories separately and mark `src/` as the source root. Use the associated project directory as the working directory for file-backed examples.

## Engineering focus

The exercises show how Java classes represent state and behavior, how inheritance specializes a shared model, and how collections of collaborating objects form a small application. The account projects extend those ideas into object persistence and communication, connecting core language concepts to application-level workflows.
