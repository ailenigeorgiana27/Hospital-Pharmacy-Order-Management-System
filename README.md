# 🏥 Hospital Pharmacy Order Management System

## 📘 Overview

This desktop application is designed to manage and process **medicine orders** between **hospital departments** and the **hospital pharmacy**. It is built following a **layered architecture** and implements the **Model-View-Controller (MVC)** design pattern. The application supports multiple terminals across departments and the pharmacy, ensuring real-time updates and interaction.

---

## 🎯 Objectives

- Streamline the internal logistics of medicine ordering within a hospital
- Provide an intuitive interface for medical personnel and pharmacists
- Enable real-time visibility of incoming orders at the pharmacy
- Reduce delays and manual communication errors between departments

---

## 🏗️ Architecture

The application follows a **3-layer architecture**:

1. **Presentation Layer (UI)** – Visual interface for hospital staff and pharmacy personnel
2. **Business Logic Layer (Services)** – Application logic for processing and validating orders
3. **Data Access Layer (Repositories)** – Handles communication with a relational database using an ORM

---

## 🧱 Technologies Used

- **Programming Language**: Java  (object-oriented)
- **UI Framework**: JavaFX 
- **Database**: SQL Server
- **ORM Library**: Hibernate / Entity Framework
- **CASE Tool for UML**: StarUML
- **Logging**: SLF4J / Serilog
- **IDE**: IntelliJ IDEA / Visual Studio

---

## ⚙️ Functionality

### 📥 Department Terminals
- Staff from hospital departments can place medicine orders
- Each order includes one or more items: a medicine and requested quantity
- Orders are instantly visible to the pharmacy upon submission

### 💊 Pharmacy Terminal
- Pharmacists can view all incoming orders, sorted by submission time
- Each order can be marked as "fulfilled" via a dedicated button
- Fulfilled orders disappear from the pharmacy view and are updated as such on the department terminal

---

## 🔁 Features

- **Real-time order tracking** between departments and the pharmacy
- **CRUD operations** for at least one core entity (e.g., `Order`, `Medicine`)
- **ORM integration** for database interaction
- **Modular, layered codebase** following best software engineering practices

---

## 📄 UML Models (Generated with CASE Tool)

Included in the `docs/UML/` folder:

- **Use Case Diagram** (with normal and alternative flows)
- **Class Diagram** (conceptual and refined versions per iteration)
- **Sequence and Communication Diagrams** (per use case per iteration)
- **Prototypes** for UI
- All diagrams kept in sync with project development (forward engineering used where applicable)

---

## 🧪 Development Stages

### 🔍 Phase I – Requirements Analysis
- Use case modeling and scenario documentation
- Iteration planning and prototype design

### 🏗️ Phase II – Iteration 1: Basic Implementation
- Sequence diagrams for first use cases
- Initial class diagram refinement
- First functional version: order creation and display

### ⚙️ Phase III – Iteration 2 & 3
- Additional interaction diagrams for remaining use cases
- Finalized class model and complete application logic
- Completed UI with full CRUD functionality and real-time updates

---
