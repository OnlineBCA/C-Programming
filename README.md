
# 💻 C Programming Basics

**Author:** Megh Badonia  
**Repository Purpose:** Learn the fundamentals of the C programming language with real code examples.

---

## 📌 Introduction to C

C is a powerful general-purpose programming language developed in the early 1970s. It is fast, efficient, and widely used for system/software development, embedded systems, and operating systems like UNIX.

C is a compiled language, meaning your code must be translated into machine code using a compiler before it can be executed.

---

## 🔤 Basic Structure of a C Program

```c
#include <stdio.h>   // Preprocessor directive

int main() {
    printf("Hello, World!\n");  // Output to console
    return 0;                   // Exit status
}
```

---

## 📦 Data Types in C

| Type     | Size (Bytes) | Description             |
|----------|--------------|-------------------------|
| `int`    | 2 or 4       | Integer numbers         |
| `float`  | 4            | Single-precision float  |
| `double` | 8            | Double-precision float  |
| `char`   | 1            | Single character        |
| `void`   | 0            | No value (used in functions) |

```c
int age = 25;
float pi = 3.14;
char grade = 'A';
```

---

## 🔧 Variables and Constants

Variables must be declared with a type before use.

```c
int number = 10;
const float GRAVITY = 9.81;  // Constant value
```

---

## 📐 Operators in C

```c
int a = 5, b = 2;

int sum = a + b;       // Addition
int diff = a - b;      // Subtraction
int prod = a * b;      // Multiplication
int div = a / b;       // Integer Division
int mod = a % b;       // Modulus

a += 1;  // Increment
b--;     // Decrement
```

---

## 🧠 if, else if, else

```c
int num = 15;

if (num > 0) {
    printf("Positive number\n");
} else if (num < 0) {
    printf("Negative number\n");
} else {
    printf("Zero\n");
}
```

---

## 🔁 Loops in C

### 1. for loop

```c
for (int i = 1; i <= 5; i++) {
    printf("%d ", i);
}
```

### 2. while loop

```c
int i = 1;
while (i <= 5) {
    printf("%d ", i);
    i++;
}
```

### 3. do-while loop

```c
int i = 1;
do {
    printf("%d ", i);
    i++;
} while (i <= 5);
```

---

## 🔣 Switch Statement

```c
int day = 3;

switch (day) {
    case 1: printf("Monday"); break;
    case 2: printf("Tuesday"); break;
    case 3: printf("Wednesday"); break;
    default: printf("Invalid day");
}
```

---

## 📞 Functions in C

```c
int add(int a, int b) {
    return a + b;
}

int main() {
    int result = add(3, 4);
    printf("Sum: %d", result);
    return 0;
}
```

---

## 🗂️ Arrays in C

```c
int numbers[5] = {1, 2, 3, 4, 5};

for (int i = 0; i < 5; i++) {
    printf("%d ", numbers[i]);
}
```

---

## 💡 Tips for Beginners

- Always end statements with a semicolon `;`
- Use comments to document your code (`// single-line`, `/* multi-line */`)
- Indent your code properly for readability
- Compile using `gcc filename.c -o output` and run with `./output`

---

## 👤 Author

Created by **Megh Badonia**

Feel free to explore, fork, or clone this repository to practice and enhance your C programming skills.

Happy coding! 🚀
