# Finance Tracker

A full-stack **personal finance management application** that helps users track income, expenses, categories, and budgets with an easy-to-use interface and analytics dashboard.
 
> This project was built collaboratively.  




---

## 🧰 Tech Stack

### **Frontend**
- React.js  
- JavaScript (ES6+)  
- HTML5, CSS3  

### **Backend**
- Node.js  
- Express.js  
- REST API Architecture  

### **Database**
- MongoDB + Mongoose ORM  

### **Tools**
- Git & GitHub  
- Postman  
- dotenv (.env for configuration)  

---

## 📁 Full Folder Structure

### **Project Root**

```bash
Finance-Tracker/
├── BackEnd/               # Backend server 
├── FrontEnd/              # React frontend application
├── screenshots/           # UI screenshots of the app
├── income_details.xlsx    # Sample income data file
├── README.md              # Project documentation
└── .gitignore             # Git ignore configuration
```

## 📌 Overview

The **Finance Tracker** is a full-stack web application designed to help users manage and monitor their personal finances in a simple and organized way. The system allows users to track **income**, **expenses**, categories, and budgets, while also providing visual insights into their financial habits. It aims to make financial planning easier by giving users a clear picture of where their money goes.

### 🔍 How the Project Works

1. **User Interaction (Frontend – React.js)**
   - The user accesses the application through a clean and responsive React-based UI.
   - Users can:
     - Add new **income** or **expense** entries  
     - Categorize transactions (Food, Travel, Bills, etc.)  
     - Set a **monthly budget**  
     - View analytical breakdowns through charts or summaries  
   - Every action performed by the user triggers an API request to the backend.

2. **API Handling (Backend – Node.js + Express.js)**
   - The backend receives each request and processes it based on the defined routes.
   - The backend handles:
     - Creating, updating, deleting transactions  
     - Managing categories  
     - Budget setup and validations  
     - User authentication (JWT) if login is implemented  
   - Controllers contain business logic, such as verifying input, formatting data, or calculating totals.

3. **Data Storage (MongoDB + Mongoose)**
   - Each transaction or budget entry is securely stored in MongoDB.
   - Mongoose models represent structured financial data like:
     - `Transaction` (type, category, amount, date)
     - `Category`
     - `Budget`
   - This ensures the data remains persistent and can be fetched at any time.

4. **Analytics & Dashboard**
   - The backend computes totals, category-wise spending, and monthly trends.
   - The frontend visualizes this data using:
     - Pie charts  
     - Bar charts  
     - Summary cards  
   - Users get a clear overview of their financial status, helping them make better financial decisions.

### 🧑‍🤝‍🧑 Group Project

Frontend - Lakshya Soni , Palak Agrawal


Backend - Marmik Kaila


Database - Karishma Rahaman

### 🎯 Purpose of the Project

The goal of the project is to build a practical, real-life application that:
- Helps users understand their spending habits  
- Encourages better budgeting and savings  
- Demonstrates full-stack development skills  
- Uses modern web technologies to provide a seamless experience  

### 🔧 Future Scope / Extendability

This project represents a **basic implementation**, but it can be expanded much further.  
Potential future enhancements include:

- Adding **user authentication with roles**
- Exporting data as **PDF/CSV reports**
- Adding **recurring transactions**
- Integrating **bank APIs** for live transaction syncing
- Implementing **AI-based spending suggestions**
- Adding mobile app support using React Native

This makes the Finance Tracker a great foundation for building a powerful, production-ready financial management system.
