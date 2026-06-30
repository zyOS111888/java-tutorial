# Java Tutorial Repository

A collection of practical Java examples covering the most commonly used concepts for beginners and junior developers.

## Prerequisites

* Java JDK 17+ (or later)
* Any Java IDE (IntelliJ IDEA, Eclipse, VS Code)
* Basic command line knowledge

---

## Topics Covered

### 1. Variables and Data Types

Learn how to declare and use variables.

```java
int age = 25;
double salary = 5000.50;
String name = "John";
```

---

### 2. Conditional Statements (If-Else)

```java
int score = 85;

if (score >= 80) {
    System.out.println("Excellent");
} else {
    System.out.println("Keep Improving");
}
```

---

### 3. Loops

```java
for (int i = 1; i <= 5; i++) {
    System.out.println("Count: " + i);
}
```

---

### 4. Methods

```java
public static int add(int a, int b) {
    return a + b;
}
```

---

### 5. Arrays

```java
int[] numbers = {10, 20, 30, 40};

for (int num : numbers) {
    System.out.println(num);
}
```

---

### 6. Object-Oriented Programming

```java
class Car {
    String brand;

    Car(String brand) {
        this.brand = brand;
    }

    void drive() {
        System.out.println(brand + " is driving");
    }
}
```

---

### 7. ArrayList

```java
ArrayList<String> fruits = new ArrayList<>();

fruits.add("Apple");
fruits.add("Orange");
fruits.add("Banana");
```

---

### 8. HashMap

```java
HashMap<String, Integer> scores = new HashMap<>();

scores.put("Alice", 90);
scores.put("Bob", 85);
```

---

### 9. Exception Handling

```java
try {
    int result = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Cannot divide by zero");
}
```

---

### 10. File Input/Output

```java
FileWriter writer = new FileWriter("sample.txt");
writer.write("Hello Java");
writer.close();
```

---

### Contributing

Feel free to submit pull requests with additional Java examples, improvements, or bug fixes.

### License

This project is licensed under the MIT License.
