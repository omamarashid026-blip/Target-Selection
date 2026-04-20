# 🧪 Week 07 Lab – Mouse-Based Target Selection Task

## 📌 Overview

This project implements an interactive experiment to measure **human motor performance** using a mouse-based target selection task. The system simulates a visual environment where users must quickly and accurately identify and click a target while ignoring distractions.

The lab is inspired by principles from Human-Computer Interaction and models key stages of human information processing.

---

## 🎯 Objective

The goal of this experiment is to measure how efficiently a user can:

* Detect a target among distractions
* Decide on the correct movement path
* Execute a precise mouse movement and click

---

## 🧠 Concepts Modeled

### 1. Perception

Users must visually identify the **correct target**:

* A *shaking green square* represents the target
* Moving red objects act as distractors

This simulates selective attention in dynamic environments.

---

### 2. Decision Making

A **diagonal guide path** is displayed to:

* Represent the decision process
* Help users plan their movement trajectory

---

### 3. Motor Execution

Users perform:

* Cursor movement
* Target acquisition (click)

The system measures **reaction and movement time**, which reflects motor performance.

---

## ⚙️ How It Works

1. The screen displays:

   * Moving distractors (ghosts 👻)
   * One shaking target 🎯
2. The user clicks on the target as fast as possible
3. The system records:

   * Time taken to click
   * Accuracy of the click

---

## 📊 Metrics Collected

* ⏱ **Movement Time** – Time between start and click
* 🎯 **Accuracy** – Whether the correct target was clicked

This can be extended to apply Fitts' Law:

```
ID = log2(D / W + 1)
```

Where:

* `D` = distance to target
* `W` = width of target

## 🚀 Features

* Real-time animation using Canvas
* Randomized moving distractors
* Shaking target behavior
* Click detection and timing
* Simple and interactive UI



## 👨‍💻 Author

Your Name: Omama Rashid
Course: CS-555
HCI AND CG

---
