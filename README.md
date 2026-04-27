# 🚀 Zedu API Automation Test Suite

**Automated API Testing Framework (JavaScript • Jest • Axios • Dotenv)**

This repository contains a fully structured, maintainable, and scalable API automation framework built for the **HNG QA Engineering Track – Stage 3 Task**.  
It tests the Zedu Platform API using clean engineering practices, dynamic authentication, and robust test design.

---

## 📌 Objectives of This Project

This project demonstrates:

- A clean, modular API automation framework  
- Programmatic authentication (no hardcoded tokens)  
- Dynamic test data generation  
- Independent, idempotent, repeatable tests  
- Meaningful assertions beyond status codes  
- Clear separation of concerns (utils, tests, config)  
- **25+ automated tests** (positive, negative, edge cases)  

---

## 🏗️ Project Structure

```bash
zedu-api-tests/
│
├── tests/
│   ├── auth.test.js
│   ├── users.test.js
│   └── orgs.test.js
│
├── utils/
│   ├── auth.js
│   ├── client.js
│   └── dataFactory.js
│
├── .env.example
├── .gitignore
├── package.json
└── README.md
