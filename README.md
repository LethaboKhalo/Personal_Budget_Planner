# Personal_Budget_Planner

# 💰 Personal Budget Planner & Expense Tracker

## 📖 Project Overview
The Personal Budget Planner and Expense Tracker is a desktop application designed to help users manage their finances efficiently. It allows users to track income and expenses, plan budgets, and visualize financial trends through interactive reports and dashboards.  

The goal of this project is to promote financial literacy by enabling users to take control of their money, understand their spending habits, and make data-driven financial decisions.

## 👩‍💻 Team Members
- Lethabo Khalo  
- Muhammed Hirsi  
- Reagile Motsepe

## 🎯 Project Features
 1. User Authentication
- Secure Sign-Up and Login functionality  
- User data validation and encrypted storage  

 2. Personal Budget Planner
- Add and manage multiple income sources  
- Plan and set monthly budgets  
- Track savings goals and spending priorities  

3. Expense Tracker
- Record expenses in real time  
- Categorize expenses (e.g., food, bills, entertainment)  
- View visual spending summaries using charts and graphs  

4. Reports & Analytics
- Generate summary reports of income vs. expenses  
- Export reports for personal recordkeeping  
- (Optional) Machine Learning integration for spending predictions and personalized tips  

## 🧠 Concepts Applied
Object-Oriented Programming (OOP):Implemented through classes like `Income`, `Expense`, `BudgetManager`, and `ReportGenerator`  
- Interfaces:`IReportGenerator` for modular report generation  
- UI/UX Design: Intuitive and user-friendly interface  
- Data Security: Safe handling and storage of user information  

## 🧩 System Design
Class Diagram Overview
- Income → Handles user income details  
- Expense → Stores and validates expense entries  
- Category → Manages expense categories  
- BudgetManager → Calculates totals, balances, and summaries  
- IReportGenerator (Interface)→ Defines reporting methods  
- ReportGenerator → Implements report generation and saving  

Relationships:
- `BudgetManager` contains multiple `Expense` objects  
- `ReportGenerator` uses `BudgetManager` to generate reports  


