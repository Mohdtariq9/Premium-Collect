# 🛡️ PremiumCollect - Insurance Premium Collection Platform

PremiumCollect is a comprehensive, responsive, frontend-only web application designed to manage insurance policyholders, calculate dues with automated tax breakdown (18% GST), collect counter payments, generate printable thermal/A4 receipts, and reconcile daily transactions.

Built entirely with **HTML5, Tailwind CSS, Vanilla JavaScript (ES6+), and Chart.js**, this application operates seamlessly in any browser with zero backend dependencies, utilizing browser `localStorage` for state persistence.

---

## ✨ Key Features

### 🔑 Authentication & Role-Based Access Control (RBAC)
- **Role Switching:** Access tailored dashboards for **Admin**, **Cashier**, and **Agent**.
- **Secure Registration & Login:** Client-side account registration with default pre-configured credentials for quick demonstration.
- **Route Protection:** Guards application views, restricting actions based on the active role session.

### 💳 Payment Collection Terminal
- **Instant Due Calculation:** Automatically computes base premium, late fees, and 18% GST.
- **Multi-Method Support:** Accepts UPI (with dynamic QR generation), Credit/Debit Card, Bank Transfer, Cash, Cheque, and Mobile Wallet.
- **Partial/Split Payments:** Flexibly handle partial installment collections.

### 🧾 Receipt Generation & Printing
- **Print-Ready Thermal & A4 Formats:** Embedded CSS `@media print` rules for instant printing or saving as PDF.
- **Verification Badges:** Includes security QR code badges and receipt IDs for audit trails.
- **Simulated Notifications:** Simulated SMS and Email receipt delivery triggers.

### 📊 Analytics & Reporting
- **Interactive Dashboards:** Visual collection trends and payment method distribution powered by Chart.js.
- **Export Options:** One-click CSV downloads for policy records, collection logs, and reconciliation reports.
- **Reconciliation Engine:** Counter ledger check, status verification, and discrepancy handling.

---

## 🛠️ Technology Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic web layout structure |
| **Tailwind CSS (v3 CDN)** | Responsive utility-first styling & Dark Mode |
| **Vanilla JavaScript (ES6+)** | State management, authentication engine, routing, dynamic UI rendering |
| **Chart.js** | Visual collection analytics and data breakdown charts |
| **Lucide Icons** | Modern UI SVG icons |
| **HTML5 LocalStorage** | Persistent mock database for users, policies, payments, and settings |

---

## 🚀 Quick Start / How to Run

1. **Clone or Download the Repository:**
   ```bash
   git clone [https://github.com/your-username/insurepay-collection-portal.git](https://github.com/your-username/insurepay-collection-portal.git)
