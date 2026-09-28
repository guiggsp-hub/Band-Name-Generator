# 🎸 Band Name Generator

> A Python command-line application that generates band names from user-provided input.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Type](https://img.shields.io/badge/project-personal-blue)

---

## 📌 About the Project

**Band Name Generator** is a personal project, developed independently, with the goal of consolidating the fundamentals of the Python language through a simple, interactive, and functional application.

The program interacts with the user through the terminal, collects two pieces of personal information (the city where they grew up and the name of a pet), and combines them to suggest a band name. Despite its small scope, the project covers the complete lifecycle of an application: **data input → processing → formatted output**.

## 🎯 Learning Objectives

This project was built to practice and demonstrate command of the following concepts:

- **Standard input and output (I/O)** using Python's built-in `input()` and `print()` functions
- **Variable declaration and usage** to store user-provided data
- **String manipulation**, particularly concatenation with the `+` operator
- **Sequential execution flow**, understanding the order in which instructions are interpreted
- **User interaction through a CLI** (Command Line Interface)

## ⚙️ How It Works

The application flow can be summarized in three stages:

```
┌──────────────────┐     ┌──────────────────────┐     ┌──────────────────────┐
│   1. Welcome     │ ──▶ │  2. Data collection  │ ──▶ │  3. Name generation  │
│     print()      │     │  input() → city, pet │     │  city + ' ' + pet    │
└──────────────────┘     └──────────────────────┘     └──────────────────────┘
```

### Code Walkthrough

```python
print('Hello! Welcome to the Band Name Generator!')
city = input('Whats the name of the city you grew up in?')
pet = input('What is the name of your pet?')
print('Nice! The name of your band could be ' + city + ' ' + pet)
```

| Line | Responsibility |
|------|----------------|
| 1 | Displays a welcome message, introducing the application to the user. |
| 2 | Prompts for the city name and stores the answer in the `city` variable. |
| 3 | Prompts for the pet's name and stores the answer in the `pet` variable. |
| 4 | Concatenates both strings, separated by a space, and displays the generated band name. |

A noteworthy detail is the explicit insertion of a space (`' '`) between the variables: since string concatenation in Python joins values without any automatic separator, this choice ensures a readable result (e.g., `Santos Rex` instead of `SantosRex`).

## 🚀 Getting Started

### Prerequisites

- [Python 3.x](https://www.python.org/downloads/) installed on your machine

### Installation and Execution

```bash
# Clone the repository
git clone https://github.com/guiggsp-hub/Band-Name-Generator.git

# Navigate to the project folder
cd Band-Name-Generator

# Run the program
python main.py
```

### Sample Run

```
Hello! Welcome to the Band Name Generator!
Whats the name of the city you grew up in? Santos
What is the name of your pet? Rex
Nice! The name of your band could be Santos Rex
```

## 🧠 Skills Demonstrated

`Programming Logic` · `Python` · `String Manipulation` · `Data Input/Output` · `CLI Applications` · `Project Documentation`

## 👤 Author

Developed independently by **Guilherme Garcia** as part of a personal programming portfolio.

[![GitHub](https://img.shields.io/badge/GitHub-guiggsp--hub-181717?logo=github)](https://github.com/guiggsp-hub)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Guilherme%20Garcia-0A66C2?logo=linkedin)](https://www.linkedin.com/in/guilherme-garcia-796633287/)
