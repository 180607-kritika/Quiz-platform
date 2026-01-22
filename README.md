

# KBC Quiz System (C)

## Overview

A console-based **Kaun Banega Crorepati (KBC) Quiz System** developed in **C**.
The application supports **Admin mode** for managing quiz questions and **Student mode** for playing a timed quiz with prize money calculation. Data is managed using **dynamic memory allocation** and **file handling**.

---

## Features

### Admin Mode

* Secure admin login
* Add, delete, update quiz questions
* View all questions
* Modify prize money
* Save questions to file

### Student Mode

* Play quiz question-by-question
* Navigate between questions
* Timed questions
* Automatic prize money calculation
* Quiz ends on wrong answer

---

## Technologies Used

* **Language:** C
* **Concepts:**

  * Structures
  * Dynamic Memory Allocation (`malloc`, `realloc`, `free`)
  * File Handling
  * String Handling
  * Conditional Compilation (Windows/Linux compatibility)

---



| File       | Description           |
| ---------- | --------------------- |
| `ques.txt` | Stores quiz questions |

Each question occupies **8 lines**:

1. Question text
2. Option A
3. Option B
4. Option C
5. Option D
6. Correct option
7. Time limit (seconds)
8. Prize money

---

## Admin Credentials (Default)

* **Username:** `admin`
* **Password:** `admin123`

---


## Menu Options

1. Admin – Manage questions
2. Student – Play quiz
3. Exit

---
