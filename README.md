# BudgetManager – Java Console Budget Management Application

**Course:** CPT206 – Java Programming (Coursework 3)  
**Author:** Ziyang Zhang (2143444)  

## Overview
BudgetManager is a console-based budget management system written in Java.  
Users can:
- record incomes and expenses with date, amount, and category  
- define budget limits for different categories  
- view summaries of total spending and check whether they exceed their budgets  

## Design
The project follows an object-oriented design with several core classes:
- `Transaction` (parent class), extended by `Income` and `Expense`
- `BudgetCategory` for storing category name, budget limit, and spent amount
- `BudgetManager` for managing all transactions and categories
- a menu-based CLI for user interaction

## Skills Demonstrated
- Object-oriented design (classes, inheritance, polymorphism)
- Input validation and exception handling
- Working with Java collections and basic file I/O
- Translating user requirements into a modular Java program

## Files in this repository
- `CPT206 CW3 Project 2143444.zip` – full Java project
- `CPT206 CW3 Report 2143444.pdf` – coursework report
