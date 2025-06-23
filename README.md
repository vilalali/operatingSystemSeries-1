# 📘 **Course Plan: Operating System**

**Goal**: Understand fundamental OS concepts and apply them in a real-world project using Python and shell. 

---

## ✅ **Class 1: Introduction to Operating Systems**

### 🎯 Objective:

Build a foundational understanding of what an OS is, what it does, and how it relates to user-level applications like text editors.

### 🧠 Topics Covered:

* What is an Operating System?
* Types of OS: Batch, Time-Sharing, Real-Time, Distributed, etc.
* Core Responsibilities of an OS:

  * **Process Management**
  * **Memory Management**
  * **File System Management**
  * **Device Management**
  * **I/O Control**
* User Mode vs Kernel Mode
* Application-level interaction with OS (CLI, GUIs, APIs)

### 📝 Activities:

* Discuss how apps like `Notepad`, `nano`, `VS Code` interact with the OS
* Group quiz: Match OS components with real-life scenarios

---

## ✅ **Class 2: Hands-On with OS Commands and Systems**

### 🎯 Objective:

Make students comfortable with working directly with the OS via terminal/shell and understand basic operations that editors rely on.

### 🧠 Topics Covered:

* Navigating the File System (Linux & Windows)
* Basic Commands:

  * `ls`, `cd`, `cat`, `touch`, `cp`, `mv`, `rm`, `chmod`, `nano`, `vi`
* File permission systems (`chmod`, `chown`)
* Process management commands:

  * `ps`, `top`, `kill`, `jobs`, `fg`, `bg`
* Understanding `/proc` and `/etc` in Linux
* Task Manager in Windows

### 💻 Activities:

* Open terminal, create a file, edit it with `nano` or `vi`
* Explore the `/proc` directory or Windows Task Manager
* Show how editors load/save files (practical behind the scenes)

---


# 📘 Project Time – Basic Text Editor

---

## ✅ **Class 3: OS Concepts Required for the Text Editor**

### 🎯 Objective:

Connect OS theory to the features of a text editor; prepare students to apply concepts in the project.

### 🧠 Topics Covered:

* **File Handling**:

  * Open, read, write, and append operations
* **Memory Management**:

  * Buffer usage and management (RAM)
* **I/O Operations**:

  * Handling keyboard input and display output
* **Processes and Threads**:

  * Autosave in the background using `threading`
  * Process vs Thread (comparison)

### 💻 Activities:

* Practice writing basic Python scripts for:

  * File reading/writing
  * Handling keyboard inputs
  * Using threading to print logs every few seconds

---

## ✅ **Class 4: Project Brief + Code Structure + Planning**

### 🎯 Objective:

Introduce the **Basic Text Editor** project, discuss required components, divide the problem, and help students begin building it.

### 🔧 Project Breakdown:

1. **File Operations** (open/save/edit text files)
2. **Text Buffering** (load into memory, modify without saving)
3. **Cursor Movement** (basic CLI or use Tkinter for GUI)
4. **Autosave Thread** (save every X seconds in background)
5. **Error Handling + Locking**

### 🧩 Skills Required:

* Python file I/O (`open`, `read`, `write`)
* Basic UI (Tkinter) or terminal-based interface
* `threading.Thread` for autosave
* Data structures for buffer (list, string ops)
* Using `Lock` for thread safety

### 💻 In-Class Build:

* Setup base folder and Python file
* Load and display file contents
* Plan modules: `buffer.py`, `editor.py`, `autosave.py`

### 📝 Assignment:

* Build basic file load and in-memory edit logic

---

## ✅ **Class 5: Project Review + Discussion + Viva**

### 🎯 Objective:

Evaluate the student submissions, share feedback, and reinforce the OS concepts applied.

### 💬 Activities:

* Each student/team presents:

  * What works
  * How they handled file & memory operations
  * How autosave or threading was implemented
* Class-wide discussion on:

  * Issues faced and debugging strategies
  * Possible feature improvements
* Viva-style Q\&A:

  * How does your text editor relate to OS internals?
  * What happens if two threads write at the same time?
  * How does the OS know what process is using the file?

### ✅ Evaluation Criteria:

* Functional correctness
* OS concept usage (file, memory, threading)
* Code structure & documentation
* Creativity (optional GUI, undo/redo, spellcheck)

---

## 📁 Tools & Requirements

| Tool                   | Purpose               |
| ---------------------- | --------------------- |
| Python                 | Programming           |
| Tkinter (optional)     | GUI                   |
| Git                    | Version control       |
| Linux/Windows Terminal | Command-line practice |
| VS Code or any IDE     | Coding                |

---

Vilal Ali
