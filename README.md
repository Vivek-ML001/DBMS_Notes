# 📘 Database Management System (DBMS) – Notes

This repository contains **structured and exam-oriented notes on Database Management Systems (DBMS)** compiled from classroom lectures and standard DBMS concepts.
These notes are suitable for **engineering students**, **semester exams**, and **quick revision**.

---

## 📌 Contents

* Introduction to DBMS
* Data → Information → Knowledge → Wisdom
* Database and DBMS Overview
* DBMS Architecture
* Metadata and Data Dictionary
* DBMS Operations (CRUD)
* Views
* Levels of Data Abstraction
* Applications of DBMS
* Advantages of DBMS
* ACID Properties

---

## 🧠 What is DBMS?

A **Database Management System (DBMS)** is software that allows users to **store, manage, retrieve, and manipulate data** efficiently.
It provides an interface between **application programs** and the **stored database**.

> DBMS = Data + Database + Management + System

---

## 📊 Data Hierarchy

* **Data** – Raw facts
* **Information** – Processed data
* **Knowledge** – Meaningful understanding
* **Wisdom** – Decision-making capability

---

## 🗄️ Database (DB)

A **database** is an organized collection of related data stored in a structured format.

* Rows → Records
* Columns → Attributes

---

## 🏗️ DBMS Architecture

The basic working of DBMS follows this flow:

**User → Application Program → DBMS Software → Database**

### Components:

* **Application Program**

  * Interacts with the user
* **DBMS Software**

  * Processes queries
  * Manages stored data
* **Query Processor**

  * Converts queries into low-level instructions
* **Storage Manager**

  * Accesses stored data and metadata
* **Database**

  * Stores actual data
* **Metadata**

  * Stores data about data

---

## 🧾 Metadata (Data about Data)

**Metadata** describes the structure of the database.

Examples:

* Table names
* Column names
* Data types
* Constraints

Metadata is stored in a **Data Dictionary**.

---

## 📖 Data Dictionary

A **Data Dictionary** is a centralized repository that stores:

* Table definitions
* Attribute details
* Constraints
* Relationships

It is automatically maintained by the DBMS.

---

## 🔁 DBMS Operations (CRUD)

* **Insert (Create)** – Add new data
* **Retrieve (Read)** – Access data
* **Update** – Modify existing data
* **Delete** – Remove data

---

## 👁️ Views

A **view** is a virtual table created using a query.

### Features:

* Shows only required data
* Improves security
* Simplifies complex queries

Views do **not** store data physically.

---

## 🧩 Levels of Data Abstraction

Data abstraction hides unnecessary details from users and shows only relevant information.

### 1. View Level (External Level)

* What the user sees
* Different users can have different views

### 2. Logical Level (Conceptual Level)

* What data is stored
* Describes structure of the database
* Tables, attributes, relationships

### 3. Physical Level (Internal Level)

* How data is stored
* File structure, indexing, storage details

---

## 🏫 Applications of DBMS

* Railway / Airline Reservation Systems
* Libraries
* Hospitals
* Universities
* Banking Systems

---

## 💻 Examples of DBMS Software

* MS Access
* MySQL
* Oracle
* PostgreSQL
* SQL Server

---

## ✅ Advantages of DBMS

* Reduced data redundancy
* Improved data consistency
* Easy data access
* Enhanced data security
* Integrity constraint enforcement

---

## 🔐 ACID Properties

ACID properties ensure **reliable database transactions**:

* **Atomicity** – All or nothing
* **Consistency** – Valid state before and after transaction
* **Isolation** – Transactions execute independently
* **Durability** – Data persists after commit

---

## 🎯 Purpose of This Repository

* Maintain organized DBMS notes
* Exam-oriented revision
* Concept clarity with diagrams
* Easy access via GitHub

---

## 📚 Author

**Vivek Kumar**
Engineering Student | Machine Learning Enthusiast

Say the word.
