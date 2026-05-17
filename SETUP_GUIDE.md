# Fintrack Pro Setup Guide

Welcome to the official setup guide for Fintrack Pro.

This document explains how to set up the project environment, install dependencies, configure services, and troubleshoot common problems.

---

# Table of Contents

1. Introduction
2. Project Overview
3. System Requirements
4. Installation Requirements
5. Environment Setup
6. Clone Repository
7. Docker Setup
8. Frontend Setup
9. Backend Setup
10. ML Service Setup
11. Database Setup
12. Running the Application
13. Troubleshooting
14. Frequently Asked Questions
15. Future Improvements

---

# 1. Introduction

Fintrack Pro is a financial technology platform designed to help users manage finances efficiently.

The application includes:

- Expense Tracking
- Budget Planning
- Investment Monitoring
- Spending Analytics
- AI-Powered Recommendations
- Financial Forecasting

This guide provides a complete installation process.

---

# 2. Project Overview

Fintrack Pro uses a microservice architecture.

Main components:

### Frontend
Responsible for:

- User Interface
- Dashboard
- Charts
- Analytics

Technologies used:

- React
- TypeScript
- Tailwind CSS

---

### Backend

Responsible for:

- API Services
- Authentication
- Data Management
- Business Logic

Technologies:

- Node.js
- Express.js
- Sequelize
- PostgreSQL

---

### Machine Learning Service

Responsible for:

- Expense Categorization
- Fraud Detection
- Forecasting

Technologies:

- Python
- FastAPI
- Scikit-learn

---

# 3. System Requirements

Recommended specifications:

### Minimum Requirements

- CPU: Intel i3
- RAM: 8GB
- Storage: 20GB free space

### Recommended Requirements

- CPU: Intel i5 or Ryzen 5
- RAM: 16GB
- Storage: SSD

---

# 4. Installation Requirements

Install the following software before starting:

### Required Tools

- Docker Desktop
- Node.js
- npm
- Python 3.10+
- PostgreSQL
- Git
- VS Code

---

# 5. Environment Setup

Before running the project:

1. Install Docker
2. Install Node.js
3. Install Python
4. Install PostgreSQL
5. Install Git
6. Install VS Code

Restart the system after installation.

---

# 6. Clone Repository

Clone the project repository.

```bash
git clone <repo-url>
```

Move into the folder:

```bash
cd Fintrack_Pro
```

---

# 7. Docker Setup

Run:

```bash
docker-compose up --build
```

This command will:

- Build backend
- Build frontend
- Build ML service
- Start PostgreSQL
- Configure networking

---

# 8. Frontend Setup

Move to frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start frontend:

```bash
npm run dev
```

Expected frontend URL:

```text
http://localhost:5173
```

---

# 9. Backend Setup

Move to backend:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Run backend:

```bash
npm run dev
```

Backend URL:

```text
http://localhost:4000
```

---

# 10. ML Service Setup

Move to ML service:

```bash
cd ml-services
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run service:

```bash
uvicorn app:app --reload
```

ML Service URL:

```text
http://localhost:8000
```

---

# 11. Database Setup

PostgreSQL database stores:

- Users
- Transactions
- Budgets
- Investments

Database setup steps:

1. Install PostgreSQL
2. Create database
3. Configure environment variables
4. Run migrations

---

# 12. Running the Application

Start all services:

```bash
docker-compose up
```

Access:

### Frontend
http://localhost:5173

### Backend
http://localhost:4000

### ML Service
http://localhost:8000

---

# 13. Troubleshooting

## Docker not running

Solution:

- Open Docker Desktop
- Start Docker service

---

## Port already in use

Solution:

Close applications using ports:

- 5173
- 4000
- 8000

---

## Node modules issue

Run:

```bash
npm install
```

Again.

---

## Python package issue

Run:

```bash
pip install -r requirements.txt
```

Again.

---

# 14. Frequently Asked Questions

### Is Docker required?

No, but recommended.

---

### Can I run locally?

Yes.

---

### Which database is used?

PostgreSQL.

---

### Is AI included?

Yes.

---

### Can new features be added?

Yes.

---

# 15. Future Improvements

Planned improvements:

- Mobile App
- Dark Mode
- Crypto Support
- Tax Calculator
- Better Forecasting
- Real Banking APIs
- Voice Assistant
- Advanced Analytics

---

# Developer Notes

Maintained by:

**Kharshavarthan N R**

GitHub Username:

**Kharsha162**

---

# Change Log

Version 1.0
- Initial Setup

Version 1.1
- Documentation Added

Version 1.2
- Analytics Improved

Version 1.3
- ML Service Added

Version 1.4
- Better Architecture

---

# Final Notes

This guide exists for setup assistance and documentation.

Contributors are encouraged to improve documentation where possible.

End of Setup Guide. 