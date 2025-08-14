# 🐸 Frog Leap Problem – Python Implementation

This repository contains a **Python solution** to the classic **Frog Leap Puzzle**, implemented in the Jupyter Notebook:  
**`Copy_of_Frog_Leap_Problem_Statement.ipynb`** (created in **Google Colaboratory**).

---

## 📜 Problem Description

The **Frog Leap Puzzle** starts with frogs arranged on lily pads:

🐸 🐸 🐸 _ 🐸 🐸 🐸

- **Two groups** of frogs face each other with an **empty pad** in between.
- The goal: **swap their positions** in the fewest moves possible.

**Rules:**
1. A frog can move **forward** into an adjacent empty pad.
2. A frog can **jump over exactly one frog** into an empty pad.
3. Frogs **cannot move backward**.

**Example:**

| Start                           | Goal                            |
|---------------------------------|----------------------------------|
| 🐸 🐸 🐸 _ 🐸 🐸 🐸 | 🐸 🐸 🐸 _ 🐸 🐸 🐸 |

*(Left-facing frogs are on the left, right-facing frogs are on the right — in the goal, they swap sides.)*

---

## 📊 Example Sequence (2 Frogs Each Side)

**Start:** 🐸 🐸 _ 🐸 🐸  
**Move 1:** 🐸 _ 🐸 🐸 🐸  
**Move 2:** _ 🐸 🐸 🐸 🐸  
**Move 3:** 🐸 🐸 🐸 _ 🐸  
**Move 4:** 🐸 🐸 🐸 🐸 _  
**Goal:** 🐸 🐸 🐸 🐸 _  

---

## 🎯 Objectives

- Model the puzzle’s state and moves programmatically.
- Implement a solver that follows puzzle rules.
- Find the **optimal** sequence of moves.
- Support various numbers of frogs on each side.

---

## 📂 Notebook Contents

- **Problem Understanding** – Rules & constraints  
- **State Representation** – Using lists/arrays  
- **Move Generation** – Valid move logic  
- **Solution Algorithm** – Recursive / iterative approaches  
- **Simulation** – Step-by-step execution  
- **Visualization** – Puzzle state after each move  
- **Extensions** – Variations and challenges  

---

## 🛠 Technologies Used

- **Python 3** – Core implementation  
- **Jupyter Notebook** – Code, explanation, and visualization  
- **Google Colaboratory** – Development and execution platform  

---

## ▶ Run in Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kdI6XTRUtTQ9Ksf9SnbRl23FMh5TOOAL#scrollTo=yWIRVXlyE_6v)

---
