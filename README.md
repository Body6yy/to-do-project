# 🚀 API Automation Project - ToDo Application

This project was developed as part of the **API Testing with Real Projects** course at **QAcart** under the mentorship of **Engineer Hatem Hatamleh **. It focuses on building a robust, automated testing framework for a real-world API.

## 🛠️ Tech Stack
- **Tool:** Postman
- **Language:** JavaScript (Postman Scripts)
- **Execution:** Postman CLI  
- **CI/CD:** GitHub Actions  

## 🎯 Key Features & Test Coverage
- **End-to-End Flows:** Automated the full user lifecycle (Register -> Login -> Create Todo -> Update -> Delete).
- **Dynamic Data:** Utilized dynamic variables to ensure unique user creation for every test run.
- **Database Management:** Integrated a **Seed API** to reset the database state, ensuring test isolation and reliability.
- **Environment Management:** Managed global/environment variables for seamless switching between stages.
- **Automated Assertions:** Comprehensive tests for status codes, response times, and JSON schema validation.

## 🚀 How to Run
1. Clone this repository.
2. Install [Newman](https://www.npmjs.com/package/newman).
3. Run the following command:
   ```bash
   newman run postman_collections/collection.json -e postman_collections/environment.json
