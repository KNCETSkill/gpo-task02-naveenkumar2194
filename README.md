[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/sywxkS3m)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22277708)
# GPO_Task02 – Java Coding Assessment

## Problem Title
Attendance Status Evaluator

## Objective
Develop a Java program that determines a student’s attendance status based on the given attendance percentage.  
This task evaluates your understanding of conditional statements, input handling using `Scanner`, and strict output formatting.

---

## Input Specification
- A single Positive integer representing attendance percentage.

---

## Output Specification
- Print **exactly one word** based on the rules below:
  - `Poor`
  - `Satisfactory`
  - `Excellent`
- Do **not** print any additional text, prompts, or symbols.
- Output is **case-sensitive**.
- No extra spaces or blank lines.

---

## Decision Rules
- Attendance > 85 → `Excellent`
- Attendance between 60 and 85 (inclusive) → `Satisfactory`
- Attendance < 60 → `Poor`

---

## Sample Test Cases

| Input | Output |
|------|--------|
| 90 | Excellent |
| 75 | Satisfactory |
| 45 | Poor |
| 60 | Satisfactory |
| 85 | Satisfactory |

---

## Instructions to Students
- Do **not** change the class name: `AttendanceStatusEvaluator`
- Write your logic **only inside the given file**
- Use `Scanner` for input
- Print output using `System.out.print()` or `System.out.println()`
- Do **not** add extra print statements

---

## Repository Structure (Do Not Modify)
