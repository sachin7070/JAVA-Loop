# Java Loops
Java Loops is a repository containing examples and explanations of loop constructs in Java.

## Table of Contents

- [Introduction](#introduction)
- [Syntax](#syntax)
- [Types of Loops](#types-of-loops)
  - [1. `for` Loop](#1-for-loop)
  - [2. `while` Loop](#2-while-loop)
  - [3. `do-while` Loop](#3-do-while-loop)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In programming, loops are used to execute a block of code repeatedly until a certain condition is met. They help in reducing redundancy and improving code readability by allowing the same set of instructions to be executed multiple times.

This repository provides explanations and examples of various loop constructs available in Java, helping developers understand how to efficiently utilize them in their code.

## Syntax

The basic syntax of a loop in Java consists of an initialization step, a condition, and an increment (or decrement) step. The general structure looks like this:

```java
for (initialization; condition; increment/decrement) {
    // code block to be executed
}
```

```java
while (condition) {
    // code block to be executed
}
```

```java

do {
    // code block to be executed
} while (condition);
```

### Types of Loops
1. for Loop
The for loop is used when you know the number of iterations in advance.

2. while Loop
The while loop is used when you want to execute a block of code repeatedly until a specified condition is false.

3. do-while Loop
The do-while loop is similar to the while loop, but it ensures that the code block is executed at least once before checking the condition.

Examples
Example 1: for Loop
```java
for (int i = 0; i < 5; i++) {
    System.out.println("Iteration: " + i);
}
```
Example 2: while Loop
```java
int i = 0;
while (i < 5) {
    System.out.println("Iteration: " + i);
    i++;
}
```
Example 3: do-while Loop
```java
int i = 0;
do {
    System.out.println("Iteration: " + i);
    i++;
} while (i < 5);
```
