# 🔀 Control Flow in Java

This section covers the fundamental control flow concepts in Java used to control the execution of programs.

Control flow statements help in making decisions, repeating tasks, and controlling program execution based on conditions.

---

## 📚 Topics Covered

### ✅ Conditional Statements
- `if`
- `if-else`
- `else-if`
- Nested `if`
- `switch`

### ✅ Loops
- `for` loop
- `while` loop
- `do-while` loop
- Nested loops

### ✅ Jump Statements
- `break`
- `continue`
- `return`

### ✅ Ternary Operator
- Conditional shorthand syntax

---

## 🧠 Why Control Flow Matters

Control flow is the foundation of programming logic and problem solving.

It is used in:
- Decision making
- Iteration and repetition
- Data processing
- Algorithm implementation
- Real-world application logic

---

## 📂 Example Structure

```bash
control-flow/
├── if-else/
├── switch/
├── loops/
├── break-continue/
└── ternary-operator/
```

---

## 💻 Sample Examples

### 🔹 If-Else

```java
int age = 20;

if(age >= 18) {
    System.out.println("Eligible to vote");
} else {
    System.out.println("Not eligible");
}
```

---

### 🔹 Switch Statement

```java
int day = 2;

switch(day) {
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    default:
        System.out.println("Invalid day");
}
```

---

### 🔹 For Loop

```java
for(int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

---

### 🔹 While Loop

```java
int i = 1;

while(i <= 5) {
    System.out.println(i);
    i++;
}
```

---

### 🔹 Ternary Operator

```java
int num = 10;

String result = (num % 2 == 0) ? "Even" : "Odd";
```

---

## ⚠️ Common Mistakes

- Infinite loops
- Missing `break` in switch
- Incorrect loop conditions
- Deep nested conditions reducing readability

---

## 💡 Key Takeaways

- Control flow determines program behavior
- Loops reduce repetitive code
- Conditions help build logical programs
- Proper flow control improves code readability and efficiency

---

## 🎯 Learning Goals

- Build strong programming fundamentals
- Understand execution flow in Java
- Prepare for DSA and backend development
- Improve problem-solving skills

---

⭐ Consistent practice is the key to mastering programming logic.
