# Java Control Flow

## Conditional Statements

### if-else
```java
if (condition) {
  // code
} else if (condition) {
  // code
} else {
  // code
}
```

### switch
```java
switch (value) {
  case 1:
    // code
    break;
  default:
    // code
}
```

### Ternary Operator
```java
result = condition ? valueIfTrue : valueIfFalse;
```

## Loops

### for
```java
for (int i = 0; i < 10; i++) {
  // code
}
```

### for-each
```java
for (Type item : collection) {
  // code
}
```

### while
```java
while (condition) {
  // code
}
```

### do-while
```java
do {
  // code
} while (condition);
```

## Jump Statements

### break
Terminates loop or switch statement.

### continue
Skips current iteration.

### return
Exits method and returns value.

### label (with break/continue)
```java
labelName: for (...) {
  break labelName;
}
```
