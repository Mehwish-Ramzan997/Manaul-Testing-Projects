# 🧪 Demoblaze.com — Manual Testing Project

![Testing](https://img.shields.io/badge/Testing-Manual-blue)
![Status](https://img.shields.io/badge/Status-Completed-green)
![TCs](https://img.shields.io/badge/Test%20Cases-34-orange)
![Pass](https://img.shields.io/badge/Pass-25-brightgreen)
![Fail](https://img.shields.io/badge/Fail-9-red)

---

## 📌 Project Overview

| Detail | Info |
|--------|------|
| 🌐 Website | [https://www.demoblaze.com/](https://www.demoblaze.com/) |
| 🏷️ App Type | E-Commerce / Product Store |
| 🛠️ Testing Type | Manual Testing |
| 📅 Test Date | May 2026 |
| 👤 Tester | QA Engineer |

---

## 📁 Repository Structure

```
Demoblaze-Manual-Testing/
│
├── README.md                        ← You are here
├── Test_Cases/
│   └── demoblaze_test_cases_EN.xlsx ← All 34 test cases
└── Bug_Report/
    └── demoblaze_bug_report.xlsx    ← All reported bugs
```

---

## 🎯 Scope of Testing

The following modules were tested on **https://www.demoblaze.com/**:

| # | Module | Description |
|---|--------|-------------|
| 1 | 🔐 Signup | New user registration flow |
| 2 | 🔑 Login | User authentication & logout |
| 3 | 🏠 Dashboard | Homepage, categories, navigation |
| 4 | 🛒 Add to Cart | Cart operations & order placement |

---

## 📊 Test Execution Summary

| Module | Total TCs | ✅ Pass | ❌ Fail | Pass Rate |
|--------|-----------|---------|---------|-----------|
| Signup | 6 | 4 | 2 | 67% |
| Login | 7 | 5 | 2 | 71% |
| Dashboard | 11 | 8 | 3 | 73% |
| Add to Cart | 10 | 8 | 2 | 80% |
| **Total** | **34** | **25** | **9** | **74%** |

---

## 🐛 Bug Summary

| Severity | Count |
|----------|-------|
| 🔴 Critical | 2 |
| 🟠 High | 3 |
| 🟡 Medium | 3 |
| 🟢 Low | 1 |
| **Total** | **9** |

> Full bug details are available in `/Bug_Report/demoblaze_bug_report.xlsx`

---

## 🔍 Test Cases Breakdown

### 🔐 Signup Module (6 Test Cases)
| TC ID | Test Case | Status |
|-------|-----------|--------|
| TC-SU-01 | Sign up with valid new credentials | ✅ Pass |
| TC-SU-02 | Sign up with already registered username | ❌ Fail |
| TC-SU-03 | Sign up with empty username field | ✅ Pass |
| TC-SU-04 | Sign up with empty password field | ✅ Pass |
| TC-SU-05 | Sign up with both fields empty | ❌ Fail |
| TC-SU-06 | Close signup modal using Close button | ✅ Pass |

### 🔑 Login Module (7 Test Cases)
| TC ID | Test Case | Status |
|-------|-----------|--------|
| TC-LG-01 | Login with valid credentials | ✅ Pass |
| TC-LG-02 | Login with incorrect password | ❌ Fail |
| TC-LG-03 | Login with a non-existent username | ❌ Fail |
| TC-LG-04 | Login with both fields empty | ✅ Pass |
| TC-LG-05 | Logout after successful login | ✅ Pass |
| TC-LG-06 | Close login modal using Close button | ✅ Pass |
| TC-LG-07 | Verify navbar state after login | ✅ Pass |

### 🏠 Dashboard Module (11 Test Cases)
| TC ID | Test Case | Status |
|-------|-----------|--------|
| TC-DB-01 | Homepage loads successfully | ✅ Pass |
| TC-DB-02 | All navbar links are visible | ✅ Pass |
| TC-DB-03 | Hero carousel/slider is visible | ✅ Pass |
| TC-DB-04 | Filter products by Phones category | ✅ Pass |
| TC-DB-05 | Filter products by Laptops category | ✅ Pass |
| TC-DB-06 | Filter products by Monitors category | ❌ Fail |
| TC-DB-07 | Product detail page opens on click | ✅ Pass |
| TC-DB-08 | Contact modal opens | ✅ Pass |
| TC-DB-09 | About Us modal opens | ✅ Pass |
| TC-DB-10 | Next / Previous pagination works | ❌ Fail |
| TC-DB-11 | Home link returns to homepage | ✅ Pass |

### 🛒 Add to Cart Module (10 Test Cases)
| TC ID | Test Case | Status |
|-------|-----------|--------|
| TC-CA-01 | Logged-in user adds product to cart | ✅ Pass |
| TC-CA-02 | Guest user adds product to cart | ✅ Pass |
| TC-CA-03 | Cart page loads correctly | ✅ Pass |
| TC-CA-04 | Added product appears in cart | ❌ Fail |
| TC-CA-05 | Total price is displayed in cart | ✅ Pass |
| TC-CA-06 | Delete a product from cart | ✅ Pass |
| TC-CA-07 | Add multiple products to cart | ❌ Fail |
| TC-CA-08 | Place Order button is visible | ✅ Pass |
| TC-CA-09 | Place Order modal opens | ✅ Pass |
| TC-CA-10 | Complete purchase with valid details | ✅ Pass |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Browser (Chrome) | Manual test execution |
| MS Excel | Test case & bug documentation |
| GitHub | Version control & portfolio |

---

## 👤 Author

**QA Engineer**
> Feel free to explore the test cases and bug reports in this repository.
