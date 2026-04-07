# 🤖 Reeborg World – Hurdles & Maze Solver

This repository contains solutions for **Reeborg World Hurdles challenges (1–3)** and a **Maze Solver**, written in Python using Reeborg’s built-in commands.

The code demonstrates progressive problem-solving concepts such as loops, functions, conditionals, and algorithmic thinking.

---

## 📌 Prerequisites

* Platform: **Reeborg World**
* Language: **Python**
* Required built-in functions:

  * `move()`
  * `turn_left()`
  * `wall_in_front()`
  * `wall_on_right()`
  * `right_is_clear()`
  * `front_is_clear()`
  * `at_goal()`

---

## 🟢 HURDLE NUMBER 1

### 🔹 Problem Description

* Fixed number of hurdles
* All hurdles have the **same height**
* Total hurdles: **6**

### 🔹 Approach

* Create helper functions for turning right
* Create a fixed jump pattern
* Use a counter-controlled loop

### 🔹 Key Concepts Used

* Functions
* `while` loop
* Code reusability

---

## 🟡 HURDLE NUMBER 2

### 🔹 Problem Description

* Hurdles appear at random positions
* Height of hurdles is **fixed**
* Number of hurdles is **unknown**

### 🔹 Approach

* Move forward until a wall is detected
* Jump whenever a wall is in front
* Continue until the goal is reached

### 🔹 Key Concepts Used

* Conditional logic (`if / else`)
* Nested loops
* Environment-based decisions

---

## 🟠 HURDLE NUMBER 3

### 🔹 Problem Description

* Hurdles have **variable heights**
* Number and position of hurdles are unknown

### 🔹 Approach

* Move up along the wall until the right side opens
* Cross the hurdle
* Descend safely on the other side

### 🔹 Key Concepts Used

* `while wall_on_right()` loop
* Dynamic obstacle handling
* Improved jumping logic

---

## 🔵 MAZE SOLVER

### 🔹 Problem Description

* Solve a maze with unknown structure
* Reach the goal from any starting position

### 🔹 Approach (Right-Hand Rule)

1. If the right path is clear → turn right and move
2. Else if front is clear → move forward
3. Else → turn left

### 🔹 Algorithm Used

* **Right-Hand Wall Following Algorithm**

### 🔹 Key Concepts Used

* Infinite loop with goal check
* Priority-based decision making
* Maze traversal strategy

---

## 🧠 Learning Outcomes

* Understanding abstraction using functions
* Mastery of loops and conditionals
* Writing clean and reusable logic
* Applying algorithms to real problems

---

## 🚀 Conclusion

This project showcases a **step-by-step evolution** from simple fixed-pattern movement to intelligent, environment-aware algorithms. It builds a strong foundation for logic development, problem solving, and future topics such as **AI pathfinding and decision-making systems**.

---

✅ *Recommended for beginners learning Python logic through Reeborg World.*

## AUTHOR
Aradhya Negi
