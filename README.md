# Insertion Sort

A Java implementation of the insertion sort algorithm with an interactive console demo.

---

## About

Written in Java, this project implements insertion sort as described in *Algorithms, 4th Edition* by Robert Sedgewick and Kevin Wayne. The algorithm sorts an integer array in place by iteratively shifting each element leftward until it reaches its correct position. Each swap is printed to the console so the progression of the sort is visible step by step.

## Usage

The program runs two back-to-back demos on startup:

1. **Interactive input** - prompts you to enter an array size and then each integer value, then sorts and prints the result.
2. **Built-in example** - sorts the hardcoded array `{1, 2, 4, 3, 5, 0}` and prints each step.

Example session for the interactive portion:

```
Enter the size of the array:
5
Enter the data:
3 1 4 1 5
Original Array:
{3, 1, 4, 1, 5}
Sorting:
...
```

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.5 or higher

### Building

**Unix / macOS**
```bash
mvn compile
```

**Windows**
```cmd
mvn compile
```

### Running

**Unix / macOS**
```bash
mvn exec:java -Dexec.mainClass="Main"
```

**Windows**
```cmd
mvn exec:java -Dexec.mainClass="Main"
```

Alternatively, compile and run directly with `javac` and `java`:

**Unix / macOS**
```bash
javac src/main/java/Main.java -d out
java -cp out Main
```

**Windows**
```cmd
javac src\main\java\Main.java -d out
java -cp out Main
```

## License

MIT - see [LICENSE](LICENSE).
