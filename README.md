# 🎯 Quiz Application

A comprehensive console-based Quiz Application developed in **Java** that simulates a real-world quiz management system using **file handling, randomized question generation, administrator controls, input validation, and persistent data storage**.

The system features separate **User** and **Administrator** functionalities, allowing users to attempt quizzes while enabling administrators to manage the question bank efficiently.

---

# ✨ Features

## 👨‍🎓 User Module

* Start a quiz from a randomized question set
* Automatic question shuffling using `Collections.shuffle()`
* 20-question quiz session
* Instant answer validation
* Correct/Wrong answer feedback
* Automatic score calculation
* Pass/Fail result generation
* Percentage calculation
* Correct answer count display

## 👨‍💼 Administrator Module

* Hidden administrator access panel
* Add new questions dynamically
* Delete existing questions
* Unique Question ID validation
* Question bank management
* Protection against duplicate question IDs
* Minimum question count enforcement

---

# 💾 File Handling

The project uses text files as a lightweight database for persistent question storage.

### Files Used

| File Name       | Purpose                                                 |
| --------------- | ------------------------------------------------------- |
| `questions.txt` | Stores all quiz questions, options, and correct answers |

---

# 📝 Question Storage Format

Each question is stored in the following format:

```text
QuestionID|Question|Option1|Option2|Option3|Option4|CorrectAnswer
```

### Example

```text
400|Capital of India?|Delhi|Mumbai|Kolkata|Chennai|1
```

Where:

* `400` → Unique Question ID
* `Capital of India?` → Question
* `Delhi` → Option 1
* `Mumbai` → Option 2
* `Kolkata` → Option 3
* `Chennai` → Option 4
* `1` → Correct Option Number

---

# 🔐 Security Features

The application includes multiple safeguards to maintain data integrity:

* Hidden administrator access mechanism
* Unique Question ID enforcement
* Duplicate question prevention
* Question existence validation before deletion
* Minimum question limit protection
* Input validation for quiz answers
* Input validation for administrative operations
* Corrupted record handling

---

# 🎮 Quiz Functionality

### Quiz Session

* Random selection of questions
* Non-repetitive quiz experience
* 20-question assessment
* Answer validation after every question
* Score tracking throughout the quiz
* Final performance report generation

### Result Generation

At the end of every quiz:

* Total Score
* Number of Correct Answers
* Percentage Obtained
* Pass/Fail Status

are displayed automatically.

---

# 📋 Question Management

### Add Question

Administrators can:

* Create new quiz questions
* Enter four answer options
* Specify the correct answer
* Store questions permanently

### Delete Question

Administrators can:

* Remove existing questions
* Delete only valid question IDs
* Prevent deletion when only 20 questions remain

This ensures that the quiz always contains enough questions for a complete assessment.

---

# ⚠️ Validation & Error Handling

The project includes extensive validation mechanisms:

* Invalid menu choice detection
* Invalid question ID detection
* Duplicate question ID prevention
* Non-existent question ID handling
* Invalid answer option handling
* Invalid quiz input handling
* File access error handling
* Corrupted question record handling
* Question count verification

---

# 🧠 Concepts Used

* Java Programming
* File Handling
* Exception Handling
* Collections Framework (`ArrayList`)
* `Collections.shuffle()`
* Input Validation
* Data Persistence
* Randomized Question Generation
* CRUD-Based Question Management
* Console-Based User Interface Design

---

# 🛠️ Technologies Used

* Java
* Java Collections Framework
* Java File Handling APIs
* BufferedReader
* BufferedWriter
* Scanner Class
* ArrayList

---

# 🚀 How to Run

## Compile the Program

```bash
javac Question_104.java
```

## Run the Program

```bash
java Question_104
```

---

# 📁 Required Files

Ensure the following file is present in the project directory before execution:

* `questions.txt`

---

# 🎯 Learning Outcomes

This project helped in understanding practical implementations of:

* Quiz Management Systems
* File-Based Data Storage
* Randomized Data Processing
* Data Validation Techniques
* CRUD Operations
* Collections Framework Usage
* Exception Handling Strategies
* Console Application Development
* Persistent Data Management
* Administrative Access Control

---

# 👨‍💻 Developed By

## Rahul Gupta

---

# 📖 Project Overview

This project was developed as a practical implementation of a Quiz Management System using Java. The objective was to create a dynamic and interactive quiz platform while gaining hands-on experience with file handling, data persistence, collections, validation techniques, and application design principles.

Unlike basic quiz programs that rely on hardcoded questions, this application maintains a persistent question bank through file storage and provides administrative controls for managing questions. The project demonstrates how core Java concepts can be used to build a complete quiz ecosystem without relying on external databases.

The application serves as an excellent learning exercise in software development, problem-solving, data management, and real-world system design.
