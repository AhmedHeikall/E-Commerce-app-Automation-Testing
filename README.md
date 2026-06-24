# 🛒 E-Commerce UI Test Automation Project

## 🎓 Graduation Project Information
This project was developed as a **Graduation Project** for the  
**Udacity Nanodegree Program**, delivered in collaboration with **Sprints.ai**,  
and **sponsored by MCIT (Ministry of Communications and Information Technology – Egypt)**.

The project demonstrates practical application of **UI Test Automation**, **BDD**, and **industry-standard automation frameworks** on a real-world E-Commerce system.

🔗 [View **certificate:**](www.udacity.com/certificate/e/3b8f9076-c714-11ec-b84e-d3c615040bc3) .
---

## 📌 Project Overview
This project automates a complete **UI test plan** for a **B2C E-Commerce web application** using **Selenium WebDriver**, **Behavior-Driven Development (BDD)**, and the **Page Object Model (POM)** design pattern.

The automation suite validates all major user workflows, including authentication, product browsing, shopping cart operations, checkout, and order creation.  
A **professional execution report** is generated after each test run, showing **PASS/FAIL status**, **execution time**, and **step-level results**.

---

## 📊 Project Summary
| Item | Description |
|-----|-------------|
| **Domain** | E-Commerce |
| **Sub-Domain** | B2C (Business to Customer) |
| **Application Type** | Public Web Application |
| **Automation Type** | UI Automation |
| **Framework** | Selenium + Cucumber (BDD) |
| **Build Tool** | Maven |
| **Design Pattern** | Page Object Model (POM) |
| **Language** | Java |
| **Reporting** | Cucumber HTML Report |

---

## 🧪 Automated Test Scenarios
The following scenarios were fully automated and validated:

| Scenario ID | Description |
|------------|------------|
| SC1 | User can register with valid data |
| SC2 | User can log in using valid email & password |
| SC3 | User can reset password successfully |
| SC4 | Logged-in user can search for products |
| SC5 | User can switch between USD & EUR currencies |
| SC6 | User can select categories & sub-categories |
| SC7 | User can filter products by color |
| SC8 | User can select product tags |
| SC9 | User can add products to shopping cart |
| SC10 | User can add products to wishlist |
| SC11 | User can add products to compare list |
| SC12 | User can complete checkout & place an order |

---

## 🏗️ Project Structure (BDD + POM)

Ecommerce-Automation/

```

├── src
│ ├── main
│ │ └── java
│ │ ├── pages
│ │ │ ├── FollowUsPage.java
│ │ │ ├── GetEmail.java
│ │ │ ├── HomeSlidersPage.java
│ │ │ ├── LoginPage.java
│ │ │ ├── RegisterPage.java
│ │ │ ├── ResetPasswordPage.java
│ │ │ ├── SearchFunctionPage.java
│ │ │ ├── SelectDifferentCategoriesPage.java
│ │ │ ├── ShoppingCartPage.java
│ │ │ ├── SwitchBetweenCurrenciesPage.java
│ │ │ └── WishlistPage.java
│ │ │
│ │ └── runner
│ │ └── RunTest.java
│
│ └── test
│ ├── java
│ │ └── stepDefinitions
│ │ ├── Hook.java
│ │ ├── SD01_Registration.java
│ │ ├── SD02_Login.java
│ │ ├── SD03_ResetPassword.java
│ │ ├── SD04_Search.java
│ │ ├── SD05_SwitchBetweenCurrencies.java
│ │ ├── SD06_SelectDifferentCategories.java
│ │ ├── SD07_HomeSliders.java
│ │ ├── SD08_FollowUs.java
│ │ ├── SD09_Wishlist.java
│ │ └── SD10_ShoppingCart.java
│ │
│ └── resources
│ └── features
│ ├── SC01_Registration.feature
│ ├── SC02_Login.feature
│ ├── SC03_ResetPassword.feature
│ ├── SC04_Search.feature
│ ├── SC05_SwitchBetweenCurrencies.feature
│ ├── SC06_SelectDifferentCategories.feature
│ ├── SC07_HomeSliders.feature
│ ├── SC08_FollowUs.feature
│ ├── SC09_Wishlist.feature
│ └── SC10_ShoppingCart.feature
│
└── README.md

```

## ⚙️ Technologies & Tools
- Java
- Selenium WebDriver
- Cucumber (BDD)
- JUnit / TestNG
- Maven
- SLF4J Logging
- IntelliJ IDEA
- ChromeDriver

## 🌟 Project Highlights
✔ Graduation Project for **Udacity Nanodegree**  
✔ Sponsored by **MCIT (Ministry of Communications and Information Technology – Egypt)**  
✔ Delivered in collaboration with **Sprints.ai**  
✔ Behavior-Driven Development (**BDD**) using **Cucumber**  
✔ **Page Object Model (POM)** architecture  
✔ Scalable and maintainable automation framework  
✔ Professional test execution and reporting  

---

## 👨‍💻 Author
**Ahmed Heikal**  
Software Test Automation Engineer  
📍 Egypt  
