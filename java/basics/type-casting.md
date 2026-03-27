# 🔄 Type Casting in Java

Type casting is converting one data type into another.

---

## 🔹 1. Implicit Casting (Widening)

Smaller → Larger type (automatic)

```java
int a = 10;
double b = a;
```

✔ No data loss  
✔ Done automatically  

---

## 🔹 2. Explicit Casting (Narrowing)

Larger → Smaller type (manual)

```java
double x = 9.8;
int y = (int) x;
```

⚠️ Data loss possible  

---

## 🔹 Type Conversion Order

```text
byte → short → int → long → float → double
```

---

## 🔹 Real Examples

```java
int num = 100;
long big = num;           // implicit

double d = 50.75;
int i = (int) d;          // explicit (loses .75)
```

---

## 🔹 Overflow Example

```java
int large = 130;
byte small = (byte) large;

System.out.println(small);  // Output: -126
```

⚠️ Data wraps around (overflow)

---

## 🔹 Mixed Type Operations

```java
int a = 5;
double b = 2.5;

double result = a + b;  // result = 7.5
```

✔ Java promotes smaller type automatically  

---

## 🔹 Casting with Division

```java
int a = 5;
int b = 2;

System.out.println(a / b);        // 2
System.out.println((double)a / b); // 2.5
```

---

## 🔹 Best Practices

- Avoid unnecessary casting
- Be careful with narrowing
- Use casting in division when needed

---

## ⚠️ Common Mistakes

- Losing data during casting
- Integer division issues
- Ignoring overflow behavior

---

## 💡 Key Takeaways

- Widening = safe  
- Narrowing = risky  
- Casting is essential in real-world calculations  