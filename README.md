# Bank Management System

A desktop ATM-like application built in Java Swing, backed by MySQL.  
Allows users to sign up, log in with a card number and PIN, and perform common banking operations (deposit, withdrawal, fast cash, mini-statement, balance enquiry, PIN change, transactions history).

---

## Table of Contents

- [Features](#features)  
- [Prerequisites](#prerequisites)  
- [Getting Started](#getting-started)  
  - [1. Clone the repo](#1-clone-the-repo)  
  - [2. Configure the Database](#2-configure-the-database)  
  - [3. Build & Run](#3-build--run) 

---

## Features

- **Multi-step Signup** (personal details → account details → final confirmation)  
- **Secure Login** with card number & PIN  
- **Deposit**, **Withdrawl**, **Fast Cash**  
- **Mini Statement** & **Full Transactions History**  
- **Balance Enquiry** and **PIN Change**  
- Custom calendar date picker (JDateChooser)  

---

## Prerequisites

- **Java JDK 8+**  
- **Apache Ant** (optional—project includes `build.xml`)  
- **MySQL Server**  
- **MySQL Connector/J** (JDBC driver)  
- **Toedter Calendar Library** (for date picker)  

---

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/<your-username>/bank-management-system.git
cd bank-management-system
