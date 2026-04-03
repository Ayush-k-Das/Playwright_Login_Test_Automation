# 🔐 Playwright Login Test Automation

## 📌 Project Overview

This project demonstrates **end-to-end automated testing** of a login functionality using **Playwright with Python and Pytest**.
It validates both **positive and negative authentication scenarios** on a sample web application.

The goal of this project is to showcase:

* UI automation testing skills
* Test case design (functional + negative testing)
* Assertion handling and validation
* Real-world QA practices

---

## 🌐 Application Under Test

URL: https://the-internet.herokuapp.com/login

---

## ⚙️ Tech Stack

* Python
* Playwright
* Pytest

---

## 📂 Project Structure

```
assert-login/
│── test_login.py     # Contains all test cases
│── README.md         # Project documentation
```

---

## 🧪 Test Scenarios Covered

### ✅ Positive Test Case

* Valid login with correct username and password
* Verifies successful navigation to **Secure Area**

### ❌ Negative Test Cases

* Invalid password
* Invalid username
* Case-sensitive username validation
* Case-sensitive password validation

### 🔍 UI Validation Test

* Verifies that login page loads correctly

---

## 🧾 Test Case Summary

| Test Case                    | Description                 | Expected Result         |
| ---------------------------- | --------------------------- | ----------------------- |
| test_is_page_login           | Check login page visibility | Login page displayed    |
| test_valid_login             | Valid credentials           | Redirect to Secure Area |
| test_wrong_password          | Incorrect password          | Error message shown     |
| test_wrong_username          | Incorrect username          | Error message shown     |
| test_case_sensitive_username | Uppercase username          | Login fails             |
| test_case_sensitive_password | Uppercase password          | Login fails             |

---

## 🚀 How to Run the Project

### 1. Install Dependencies

```bash
pip install pytest playwright
playwright install
```

### 2. Run Tests

```bash
pytest
```

---

## 📊 Test Execution Result

* Total Tests: 6
* Status: ✅ All Passed
* Execution Time: ~31 seconds

---

## 🧠 Key Learning Outcomes

* Writing **automated UI test scripts**
* Using Playwright locators (label, role, XPath/CSS)
* Implementing **assertions using expect()**
* Handling **positive and negative test scenarios**
* Understanding real-world login validation flows

---

## 📈 Future Enhancements

* Add **test reporting (HTML reports)**
* Integrate with **CI/CD pipeline (GitHub Actions)**
* Expand to **cross-browser testing**
* Implement **data-driven testing**

---

## 👨‍💻 Author

Ayush Das
Computer Science Undergraduate | Aspiring QA Engineer

---
