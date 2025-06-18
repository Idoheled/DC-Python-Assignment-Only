# DC Team Python Assignment – Knowledge-Building Task

This task is designed to significantly enhance the DC Team’s knowledge and proficiency with essential tools and Python development.

---

## 📦 Tools to Install

To successfully complete this assignment, please install the following tools on your computer and get familiar with how to use them:

1. Docker Desktop  
2. Anaconda  
3. Visual Studio Code  
4. Robo3T or MongoDB Compass  
5. Git Bash  

---

## ⚠️ Rules

Throughout this task, you will be required to dive deep into several technical areas. Prepare yourself for a challenging yet rewarding learning experience.

✅ **Using AI is allowed**, but **do NOT copy and paste this entire task into an AI tool for full code generation**. The goal is to learn, not to copy-paste.

---

## 🎯 Objective

Your goal is to develop an application that performs **insertion**, **retrieval**, and **modification** of records in a database.

---

## 📝 Task Breakdown

### 1. 🗂️ Project Setup with Git

- Create a **public Git repository** to host your code.
- Work with **two branches**:
  - `main` or `master` – for the final, production-ready version.
  - `dev` – for daily progress and experiments.
- Every push should include a **clear and descriptive commit message**.

---

### 2. 🐳 MongoDB Container Setup

- Use Docker to **run a MongoDB container** (image from Docker Hub).
- Connect to it using Robo3T or MongoDB Compass.
- Create a **database and collection** named **`DCTeam`** (case-sensitive).

---

### 3. 🐍 Python FastAPI Application

Create a full Python project using **FastAPI** including:

- `Dockerfile`
- `docker-compose.yml`
- `requirements.txt`

#### Your FastAPI app (with Swagger UI) must support:

| Method | Endpoint           | Description                                          |
|--------|--------------------|------------------------------------------------------|
| GET    | `/equipment`           | Retrieve all documents                              |
| GET    | `/equipment/{id}`      | Retrieve a specific document by unique ID           |
| POST   | `/equipment`           | Insert a new document into the database             |
| DELETE | `/equipment/{id}`      | Delete a document by unique ID                      |
| PATCH  | `/equipment/{id}`      | Update a single field in a specific document        |
| PUT    | `/equipment/{id}`      | Fully update a specific document                    |

---

### 🧾 Document Structure

Each document in your collection represents a **server** with the following fields:

- `vendor` – Server manufacturer (e.g., Dell, HP)  
- `serial` – Server serial number  
- `arrival_date` – Date the server entered the warehouse  
- `warranty_end_date` – Warranty expiration date  
- `part_number` – Product part number  

---

### 4. 🧱 Docker Compose Integration

- Launch your **FastAPI application** in a Docker container.
- Ensure it communicates correctly with the **MongoDB container**.
- Use your MongoDB GUI tool to verify changes.

---

### ⭐ Bonus (Optional)

Implement **authentication** so that access to your Swagger UI is protected with a **username and password** that you define. Unauthorized users should not be able to access the API.

---

## 📌 Guidelines

- Use the listed tools.
- Research online as needed.
- Pause regularly to reflect on what you've changed and document it.

---

## ✅ Requirements

- Clear, readable **comments** in the code  
- Well-structured and organized **codebase**  
- Meaningful **variable names**  
- Usage of **functions** and Pythonic code patterns  
- Logical **file and folder structure**

---

## 💡 Tips

Before starting installations or coding:

- Spend ~1 hour discussing the assignment with **ChatGPT** (don't paste this task directly). Use it to plan your approach and structure.
- Identify **milestones** and **checkpoints**.
- You will be asked to explain your work and decisions at the end.

---

## 🚀 Good Luck!

I'm available for any questions you may have along the way. You're encouraged to learn, explore, and build something you're proud of!