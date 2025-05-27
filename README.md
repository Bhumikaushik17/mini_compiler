# mini_compiler
# 🧠 C++ Compiler Simulator with Tree Visuals

A **Python-based compiler simulator** designed to demonstrate the core stages of a C++ compiler in a user-friendly and visual manner. This project is ideal for students, educators, and anyone curious about how a compiler works under the hood — especially in the early stages like **Lexical Analysis**, **Parsing**, **AST generation**, and **Intermediate Code Generation**.

---

## 🎯 Objective of the Project

The primary goal of this project is to **simulate the front-end phases of a C++ compiler** in a way that is **educational, interactive, and visual**. Compilers are at the heart of programming, yet their internal processes can often seem abstract and difficult to grasp — especially for beginners. This project aims to bridge that gap.

### 🔍 Key Objectives:

- **Understand Compiler Structure:**
  - Demonstrate how source code is processed step-by-step in a compiler.
  - Focus on the early compiler phases: **Lexical Analysis**, **Syntax Analysis**, **AST construction**, and **Intermediate Code Generation**.

- **Visualize the Compilation Process:**
  - Generate clear, graphical representations of the parse tree and abstract syntax tree.
  - Make compiler internals visible to the user, enhancing comprehension through visualization.

- **Showcase Intermediate Code Generation:**
  - Illustrate how expressions are broken down into low-level operations (3-address code).
  - Demonstrate basic code optimization techniques in a simplified form.

- **Provide an Interactive Learning Tool:**
  - Allow students to enter C++ code and immediately see how it's tokenized, parsed, and converted into intermediate code.
  - Empower users to experiment with different code snippets and observe how the compiler reacts.

- **Promote Hands-On Learning:**
  - Encourage students and beginners to modify and extend the compiler logic.
  - Make compiler design less intimidating by offering a friendly GUI environment.

---

## 📚 Project Overview

This simulator provides a graphical interface where users can input simple C++ code and visualize how it is processed internally by a compiler. It handles:

1. **Lexical Analysis** — Breaking the input code into categorized tokens.
2. **Parse Tree Construction** — Displaying the structure of tokenized code visually.
3. **AST (Abstract Syntax Tree)** — Filtering out non-essential tokens (like separators) and showing a cleaner version.
4. **Intermediate Code Generation** — Generating 3-address code with temporary variables.
5. **Code Optimization** — Applying basic optimizations like removing operations with neutral elements (e.g., `*1`, `+0`).

---

## 🛠 Features

| Feature                  | Description |
|--------------------------|-------------|
| 🧾 **Lexical Analyzer**   | Scans the input code and identifies keywords, identifiers, operators, numbers, etc. |
| 🌲 **Parse Tree Generator** | Visualizes the entire stream of tokens as a tree (image format using Matplotlib). |
| 🌳 **AST Generator**      | Eliminates separators (like `;`, `(`, `)`) and presents a cleaner, meaningful tree. |
| ⚙️ **Intermediate Code**  | Generates 3-address code (TAC) from assignment expressions. |
| 🧹 **Code Optimizer**     | Applies basic optimizations like removing `*1` or `+0` to simplify code. |
| 🖼️ **Visual Output**      | Tree diagrams are rendered and displayed dynamically in the GUI. |
| 💻 **User-Friendly GUI**  | Built with `Tkinter`, the interface is responsive, scrollable, and interactive. |

---





