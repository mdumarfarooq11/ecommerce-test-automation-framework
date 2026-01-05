# E-Commerce Test Automation Framework

## 📌 Overview
A scalable Selenium-based test automation framework built from scratch using Python and PyTest.  
Designed using the Page Object Model (POM) for maintainability and reusability.

## 🛠 Tech Stack
- Python
- Selenium WebDriver
- PyTest
- Page Object Model (POM)
- Allure Reports
- Git & GitHub
- AWS S3 (report storage – planned)

## 📂 Project Structure
AUTOMATION_FRAMEWORK
│
├── pages/ # Page classes & locators
├── tests/ # Test cases
├── Extras/ # Docs, roadmap, notes
├── project_env/ # Virtual environment (ignored)
│
├── requirements.txt
├── pytest.ini
├── .gitignore
└── README.md


## ✅ Features
- Modular Page Object Model design
- Reusable test components
- Data-driven testing support
- PyTest fixtures for setup & teardown
- Allure reporting integration
- CI/CD ready structure

## ▶️ How to Run
```bash
pip install -r requirements.txt
pytest -v


📌 Future Enhancements

Parallel execution
CI integration (GitHub Actions / Jenkins)
Cloud execution