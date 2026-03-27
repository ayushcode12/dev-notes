# ⚙️ Operators in Java

Operators are used to perform operations on variables and values.

---

## 🔹 1. Arithmetic Operators

Used for basic mathematical operations.

| Operator | Meaning        | Example        |
|----------|----------------|----------------|
| +        | Addition       | a + b          |
| -        | Subtraction    | a - b          |
| *        | Multiplication | a * b          |
| /        | Division       | a / b          |
| %        | Modulus        | a % b          |

```java
int a = 10, b = 3;

System.out.println(a + b); // 13
System.out.println(a % b); // 1
```

---

## 🔹 2. Unary Operators

Operate on a single operand.

| Operator | Meaning         |
|----------|-----------------|
| +        | Unary plus      |
| -        | Unary minus     |
| ++       | Increment       |
| --       | Decrement       |
| !        | Logical NOT     |

```java
int x = 5;

System.out.println(++x); // 6 (pre-increment)
System.out.println(x--); // 6 (post-decrement)
System.out.println(x);   // 5
```

---

## 🔹 Pre vs Post Increment

```java
int a = 5;

System.out.println(++a); // 6 (first increment, then use)
System.out.println(a++); // 6 (use, then increment)
System.out.println(a);   // 7
```

---

## 🔹 3. Relational (Comparison) Operators

Used to compare values → result is boolean.

| Operator | Meaning          |
|----------|------------------|
| ==       | Equal to         |
| !=       | Not equal        |
| >        | Greater than     |
| <        | Less than        |
| >=       | Greater or equal |
| <=       | Less or equal    |

```java
int a = 10, b = 5;

System.out.println(a > b);  // true
System.out.println(a == b); // false
```

---

## 🔹 4. Logical Operators

Used with boolean expressions.

| Operator | Meaning       |
|----------|---------------|
| &&       | AND           |
| ||       | OR            |
| !        | NOT           |

```java
int age = 20;

System.out.println(age > 18 && age < 30); // true
System.out.println(age < 18 || age > 25); // false
```

---

## 🔹 Short-Circuit Behavior

```java
int a = 5;

if (a > 0 && ++a > 5) {
    System.out.println(a);
}
```

✔ `&&` stops if first condition is false  
✔ `||` stops if first condition is true  

---

## 🔹 5. Assignment Operators

Used to assign values.

| Operator | Meaning          |
|----------|------------------|
| =        | Assign           |
| +=       | Add and assign   |
| -=       | Subtract assign  |
| *=       | Multiply assign  |
| /=       | Divide assign    |
| %=       | Modulus assign   |

```java
int x = 10;

x += 5;  // x = x + 5 → 15
x *= 2;  // x = 30
```

---

## 🔹 6. Bitwise Operators (Advanced)

Operate at binary level.

| Operator | Meaning |
|----------|--------|
| &        | AND    |
| |        | OR     |
| ^        | XOR    |
| ~        | NOT    |
| <<       | Left shift |
| >>       | Right shift |

```java
int a = 5;  // 0101
int b = 3;  // 0011

System.out.println(a & b); // 1
System.out.println(a | b); // 7
```

---

## 🔹 7. Ternary Operator

Shortcut for if-else.

```java
int a = 10;

String result = (a > 0) ? "Positive" : "Negative";
```

---

## 🔹 Operator Precedence (Important)

Order of execution:

```text
1. Unary (++, --, !)
2. Arithmetic (*, /, %)
3. Arithmetic (+, -)
4. Relational (<, >, <=, >=)
5. Equality (==, !=)
6. Logical (&&, ||)
7. Assignment (=, +=, etc.)
```

---

## ⚠️ Common Mistakes

- Using `=` instead of `==`
- Integer division issues (`5 / 2 = 2`)
- Confusing pre/post increment
- Ignoring short-circuit behavior

---

## 💡 Key Takeaways

- Operators are core to all logic building
- Understand precedence to avoid bugs
- Use ternary for clean conditions
- Be careful with increment and division