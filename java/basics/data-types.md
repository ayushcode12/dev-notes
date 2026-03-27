# 📌 Data Types in Java

Java is a **strongly typed language**, meaning every variable must have a defined type.

---

## 🔹 Primitive Data Types

| Type    | Size | Example              |
|---------|------|----------------------|
| byte    | 1B   | byte b = 10;         |
| short   | 2B   | short s = 1000;      |
| int     | 4B   | int i = 100000;      |
| long    | 8B   | long l = 100000L;    |
| float   | 4B   | float f = 10.5f;     |
| double  | 8B   | double d = 99.99;    |
| char    | 2B   | char c = 'A';        |
| boolean | 1bit | boolean flag = true; |

---

## 🔹 Important Notes

- Default integer type → `int`
- Default decimal type → `double`
- `long` requires `L` suffix
- `float` requires `f` suffix

```java
long population = 7800000000L;
float price = 10.5f;
```

---

## 🔹 Non-Primitive Data Types

- String
- Arrays
- Classes
- Objects

```java
String name = "Ayush";
```

---

## 🔹 Type Ranges (Important for Interviews)

| Type  | Range |
|------|------|
| byte | -128 to 127 |
| short| -32K to 32K |
| int  | ~ -2B to 2B |
| long | very large |

---

## 🔹 When to Use What?

- `byte/short` → rarely used (memory optimization)
- `int` → most common
- `long` → large values (IDs, population)
- `double` → default for decimals
- `float` → when memory is critical

---

## ⚠️ Common Mistakes

- Forgetting `L` in long
- Forgetting `f` in float
- Using `int` for large numbers
- Confusing `char` with `String`

---

## 💡 Key Takeaways

- Choose correct data type based on size
- Java is strict with types
- Always use proper suffixes (`L`, `f`)