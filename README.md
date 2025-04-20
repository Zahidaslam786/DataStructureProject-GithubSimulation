# GitHub Simulation (C++ Console Application)

A console-based GitHub simulation developed in C++ that mimics core features of the real GitHub platform. This project demonstrates the application of Object-Oriented Programming (OOP) and Data Structures such as AVL trees and Graphs to implement user and repository management, file handling, commit tracking, and social interactions (follow/unfollow).

## 🚀 Project Overview

This simulation provides a simplified GitHub-like experience where users can:

- Register and log in
- Create and manage repositories
- Add, commit, and delete files
- Fork repositories
- Follow and unfollow other users

All operations are handled via a command-line interface, built with C++ and structured through modular, reusable classes.

---

## 🔑 Key Features

### 👤 User Registration & Authentication
- Register with a unique username and password
- Secure login with input validation
- Persistent user sessions (within runtime)

### 📦 Repository Management
- Create public or private repositories
- Delete existing repositories
- View repository details and contents

### 🌿 Forking & Collaboration
- Fork other users’ public repositories
- View and interact with repositories owned or forked
- Build a simulated collaboration environment

### 📁 File & Commit Operations
- Add and delete files in repositories
- Create commits with messages and unique hash values
- Track commit history per repository

### 🤝 User Interaction
- Follow or unfollow other users
- View own and others' profiles
- Simple graph-based relationship structure

---

## ⚙️ Technical Details

### 🧱 Classes & Structures

- **User**: Handles registration, login, profile, follow/unfollow features.
- **Repository**: Manages files, visibility, and commits.
- **File**: Represents individual files in repositories.
- **Commit**: Stores hash and commit message.
- **AVL Tree**: Stores repositories and enables fast search operations.
- **Graph**: Represents user relationships (followers/following).
- **GitHub (Main Class)**: Connects all modules and handles command-line interaction.

### 🧠 Algorithms & Data Structures Used

- **AVL Trees** for balanced and efficient repository storage.
- **Graphs (Adjacency List)** for managing user relationships.
- **Hashing** for unique commit identification.
- **OOP Principles**: Inheritance, Encapsulation, Abstraction, and Polymorphism.

---

## 🖥️ UI & Interaction

- Clear text-based menus
- Color-coded outputs for better readability
- Console-based UI with structured navigation

---

## 📌 Future Enhancements

- Implement branching and merging
- Add user profile customization
- Introduce real-time notifications or activity feeds
- Save/load system state using file I/O for persistence

---

## 📚 Learning Outcomes

This project demonstrates core principles of:

- Software design with OOP in C++
- Applying data structures in real-world simulations
- Building interactive CLI-based applications
- Understanding version control system logic

---

## ✅ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/github-simulation.git
