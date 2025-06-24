
# 🏦 Banking Web Application (Flask + SQLite + Docker)

A basic yet functional web-based banking system built using Flask. It allows users to create accounts, check balances, deposit and withdraw money. The application is also containerized using Docker for easy deployment.

---

## 🎯 Objective

The objective of this project is to develop a simple banking system that performs core operations such as:

- Creating a bank account
- Checking account balance
- Depositing and withdrawing funds
- Displaying a clean user interface with basic navigation
- Deploying the app in a containerized environment using Docker

This app is ideal for understanding how a minimal full-stack banking system works.

---

## 💻 Tech Stack

| Layer        | Technology Used      |
|--------------|----------------------|
| Backend      | Python, Flask         |
| Database     | SQLite                |
| Frontend     | HTML & CSS (inline with Flask templates) |
| Containerization | Docker           |

---

## 🛠️ Steps Included

### 1. **Database Setup**
- Uses SQLite for lightweight storage.
- Initializes a database (`bank.db`) on app launch with a single table `accounts`:
  - `id`: Integer (Primary Key)
  - `name`: Text
  - `balance`: Real (Float)

### 2. **Features Implemented**
- **Home Page** – Displays welcome message and navigation bar.
- **Create Account** – Accepts name and initial balance; inserts a new record.
- **Check Balance** – Queries and displays account balance using account ID.
- **Deposit** – Adds a specified amount to an account's balance.
- **Withdraw** – Deducts a specified amount from balance with validation.
- **Statement** – Placeholder for future transaction history feature.

### 3. **Docker Integration**
- `Dockerfile` included for containerized deployment.
- Exposes Flask app on port `5005`.

---

## 🔍 Key Insights

- Demonstrates end-to-end flow of form handling using Flask routes and templates.
- Shows how to manage database connections and execute queries securely.
- Highlights how to integrate Flask apps into Docker for platform-independent deployment.
- Encourages modular and readable code with route-wise separation.
- Ready for future enhancements like:
  - Transaction history
  - Authentication
  - RESTful APIs

---

## 🚀 How to Run

### 🧱 Clone Repository
```bash
git clone https://github.com/your-username/banking-app.git
cd banking-app
