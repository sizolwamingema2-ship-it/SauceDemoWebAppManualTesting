# SauceDemoWebAppManualTesting
Manual Testing of Sauce Demo Web Application

# 🧪 Sauce Demo Manual Testing Project

## 📌 Project Overview

Welcome to my Manual Software Testing portfolio project.

This project demonstrates my practical experience in **Manual Software Testing and Quality Assurance (QA)** using the Sauce Demo web application.

The project was created to practice the complete manual testing process, from planning and designing test scenarios and test cases to executing tests, documenting defects, analysing results, and preparing a final test summary report.

This project represents one of the practical steps in my journey toward becoming a **Software Tester / QA professional**.

---

## 🎯 Project Objective

To evaluate the functionality of the Sauce Demo web application by performing manual testing on key user workflows and identifying defects.

---

## 🔍 Scope of Testing

The following application modules were tested:

- 🔐 **Login**
- 📦 **Inventory**
- 🛒 **Cart**
- 💳 **Checkout**

Testing focused on the functionality and behaviour of these key user workflows.

---

## 🧪 Testing Approach

Manual functional testing was performed using structured QA documentation and test execution.

The testing process included:

- Test Scenario Design
- Test Case Design
- Positive Testing
- Negative Testing
- Functional Testing
- Test Execution
- Expected vs Actual Result Comparison
- Defect Identification
- Defect Reporting
- Severity Classification
- Priority Classification
- Test Result Analysis
- Test Summary Reporting

---

## 🛠️ Test Environment

| Item | Details |
|---|---|
| Application Under Test | Sauce Demo Web Application |
| Testing Type | Manual Functional Testing |
| Test Environment | Web Browser |
| Testing Approach | Manual Testing |

---

## 📊 Test Execution Results

A total of **38 test cases** were executed across the Login, Inventory, Cart, and Checkout modules.

| Module | Total Test Cases | Passed | Failed | Not Run | Pass Rate |
|---|---:|---:|---:|---:|---:|
| Login | 10 | 9 | 1 | 0 | 90% |
| Inventory | 10 | 10 | 0 | 0 | 100% |
| Cart | 10 | 9 | 1 | 0 | 90% |
| Checkout | 8 | 8 | 0 | 0 | 100% |
| **TOTAL** | **38** | **36** | **2** | **0** | **94.74%** |

### 📈 Overall Result

**36 of 38 test cases passed**, resulting in an overall pass rate of **94.74%**.

No test cases were left unexecuted.

---

## 🐞 Defects Identified

A defect was documented during testing in the **Cart** module.

### BUG_001 — Cart Subtotal Is Not Displayed

| Defect Attribute | Details |
|---|---|
| Defect ID | BUG_001 |
| Module | Cart |
| Test Case | TC_CART_007 |
| Severity | Medium |
| Priority | Medium |
| Status | Open |

### Defect Description

The cart did not display a subtotal after a product was added to the cart.

The defect was documented with:

- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Status
- Comments

The defect remains open for further investigation and resolution.

---

## 📁 Project Structure

```text
SauceDemo-Manual-Testing/
│
├── README.md
│
├── Test-Scenarios/
│
├── Test-Cases/
│
├── Bug-Reports/
│
├── Test-Execution/
│
├── Test-Summary/
│
└── Evidence/
