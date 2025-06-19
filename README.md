## Node.js + Mongoose + MongoDB Setup Guide + CRUD Operations

This guide helps you set up a backend application using **Mongoose** to communicate with a **MongoDB** database and with **CRUD Operations**

---

## Concepts

### Schema

A **schema** defines the structure of your documents — it is basically a blueprint of your data.

### Model

A **model** is created using a schema and is used to interact with the database (e.g., performing queries).

### CRUD Operations

We perform CRUD operations using model methods like:

- `.find()`
- `.findById()`
- `.findByIdAndDelete()`
- `.save()`, etc.

---

## Setup Instructions

### Step 1: Set Execution Policy (for Windows PowerShell)

Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

### Step 2: Initialize Node Project

npm init -y

### Step 3: Install Required Packages

npm install express mongoose nodemon dotenv

### Step 4: Run the Project with Nodemon

npx nodemon index.js

### Step 5: Follow Mongoose-MongoDB Connection Guide

Refer to step 5 from this TopCoder tutorial:
How to Connect MongoDB to Node.js Using Mongoose

---

Environment Variables
If you want to create a .env file and face any issues, watch this tutorial:
Watch from 15:00 - YouTube Guide

---
