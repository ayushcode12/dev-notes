# 📌 Variables in Java

Variables are used to store data values in memory.

---

## 🔹 Declaration & Initialization

```java
int age = 21;          // declaration + initialization
double price;          // declaration
price = 99.99;         // initialization
```

---

## 🔹 Types of Variables

### 1. Local Variables
- Declared inside methods
- Must be initialized before use

```java
public void example() {
    int x = 10;
}
```

---

### 2. Instance Variables
- Declared inside class, outside methods
- Belong to object

```java
class Student {
    int age;
}
```

---

### 3. Static Variables
- Shared among all objects
- Declared using `static`

```java
class Student {
    static String school = "ABC School";
}
```

---

## 🔹 Naming Rules

- Must start with letter, `_`, or `$`
- Cannot start with number
- Case-sensitive (`age` ≠ `Age`)
- Cannot use reserved keywords

---

## 🔹 Naming Conventions (Best Practice)

```java
int studentAge;     // camelCase
double totalPrice;
boolean isActive;
```

---

## 🔹 Default Values (for instance variables)

| Type     | Default Value |
|----------|--------------|
| int      | 0            |
| double   | 0.0          |
| boolean  | false        |
| object   | null         |

---

## 🔹 Constants (final keyword)

```java
final double PI = 3.14159;
```

- Value cannot be changed
- Use uppercase naming

---

## ⚠️ Common Mistakes

- Using uninitialized local variables
- Poor naming (`a`, `b`, `x1`)
- Confusing static and instance variables

---

## 💡 Key Takeaways

- Variables store data
- Scope matters (local vs instance vs static)
- Use meaningful names
- Prefer constants for fixed values