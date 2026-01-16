# discrete-math-exam-assistant
A LLM-based assistant for discrete mathematics exam preparation

## Project Overview

This project implements an **LLM-based Discrete Mathematics Exam Preparation Assistant** with a strong emphasis on **prompt engineering and iterative refinement**.

Rather than treating the language model as a generic tutor, this project explores how **carefully designed prompts** can control the model’s behavior to support different exam-oriented goals.

---

## Prompt Engineering Methodology

The core of this project lies in **three iterations of prompt design**, each reflecting a deeper level of task control and exam awareness.

### 🔹 Iteration 1: General Exam Preparation

The first prompt focuses on basic exam preparation:

* Generating study plans
* Identifying key topics
* Providing practice questions

This iteration establishes a functional baseline but does not explicitly target scoring optimization.

---

### 🔹 Iteration 2: High-Score Oriented Optimization

The second iteration refines the prompt to:

* Emphasize high-frequency exam topics
* Highlight common point-loss traps
* Enforce exam-style answer structures

At this stage, the model is guided to prioritize **scoring efficiency rather than general understanding**.

---

### 🔹 Iteration 3: Examiner-Oriented Reverse Design

The final iteration shifts perspective to that of an **examiner and grader**:

* Reverse-engineering exam design logic
* Explicitly modeling grading rubrics
* Comparing full-mark, partial-mark, and incorrect answers

This iteration demonstrates advanced prompt control by aligning model outputs with **evaluation criteria used in real exams**.

---

## Key Insight

Through prompt iteration, the same language model can be systematically guided to:

* Act as a tutor
* Act as a high-score coach
* Act as an examiner

This project highlights how **prompt design directly shapes model reasoning style, output structure, and practical usefulness** in educational applications.
