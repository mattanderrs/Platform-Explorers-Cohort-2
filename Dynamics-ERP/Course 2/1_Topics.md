# Week 02 – General Ledger, Chart of Accounts & Currency

## Objectives
By the end of this week, trainees will be able to:
- Understand the structure of the General Ledger in D365FO
- Design a basic Chart of Accounts (COA)
- Understand financial dimensions and their purpose
- Understand how currency works in ERP systems
- Explain how transactions impact financial reporting

## Topics Covered
- Record-to-Report (R2R) overview
- Ledger and fiscal periods
- Chart of Accounts (COA)
- Main accounts (P&L and Balance Sheet)
- Financial dimensions (conceptual)
- Currency types (accounting, reporting, transaction)

## Contents
- Use Case: BlueContoso Financial Setup
- Lab: General Ledger Foundation Configuration
- Assessment: Week 02 Knowledge & Consulting Checkpoint


.



# 📊 Accounting Fundamentals for D365FO

## 🔍 Overview
This page introduces the **core accounting concepts** required for Week 2.

These concepts are essential to understand:
- General Ledger
- Chart of Accounts (COA)
- Financial postings in D365FO

---

## 🎯 Learning Outcomes

By the end of this page, you will be able to:

- Understand the difference between **Balance Sheet** and **Profit & Loss**
- Explain how transactions impact financial statements
- Identify key account types in ERP systems
- Relate accounting concepts to D365FO configuration

---

# 🧱 Core Accounting Structure

Accounting is built on two key perspectives:

| Question | Report |
|--------|-------|
| What does the company own and owe? | Balance Sheet |
| Is the company making money? | Profit & Loss |

---

# 🟦 Balance Sheet (Financial Position)

## 📌 Definition
The Balance Sheet shows the **financial position of a company at a specific point in time**.

> Think: "Where do we stand TODAY?"

---

## ⚖️ Accounting Equation
Assets = Liabilities + Equity

This equation must ALWAYS balance.

---

## 🧩 Components

### 🟢 Assets (What the company owns)
Examples:
- Cash
- Inventory
- Equipment
- Customer receivables

✅ D365FO Examples:
- Bank accounts
- Inventory accounts
- Customer balances

---

### 🔴 Liabilities (What the company owes)
Examples:
- Vendor payables
- Loans
- Tax obligations

✅ D365FO Examples:
- Vendor balances
- Accrued expenses

---

### 🟡 Equity (Owner’s interest)
Examples:
- Owner capital
- Retained earnings

---

## 🧠 Key Characteristics

- Snapshot at a moment in time
- Always balanced
- Shows financial health

---

## ✅ Example

| Assets | Amount |
|------|-------|
| Cash | 10,000 |
| Inventory | 5,000 |
| **Total** | 15,000 |

| Liabilities | Amount |
|------------|-------|
| Payables | 4,000 |

| Equity | Amount |
|--------|-------|
| Capital | 11,000 |

✅ Equation holds:

15,000 = 4,000 + 11,000

---

# 🟩 Profit & Loss (P&L)

## 📌 Definition
The Profit & Loss statement shows the **performance over a period of time**.

> Think: "Did we make money THIS MONTH?"

---

## 💰 Formula


Profit = Revenue - Expenses

---

## 🧩 Components

### 🟢 Revenue
Examples:
- Sales income
- Service income

✅ D365FO:
- Sales invoice postings

---

### 🔴 Expenses
Examples:
- Cost of goods sold
- Rent
- Salaries

✅ D365FO:
- Expense accounts
- Purchase-related postings

---

## 🧠 Key Characteristics

- Covers a time period
- Shows profitability
- Does NOT include assets or liabilities

---

## ✅ Example

| Description | Amount |
|------------|-------|
| Revenue | 20,000 |
| COGS | 8,000 |
| Expenses | 5,000 |
| **Profit** | 7,000 |

---

# 🔁 Balance Sheet vs P&L (CRITICAL)

| Aspect | Balance Sheet | P&L |
|------|-------------|-----|
| Type | Position | Performance |
| Time | Point in time | Period |
| Includes | Assets, Liabilities, Equity | Revenue, Expenses |
| ERP impact | Ongoing balances | Period results |

---

# 🔗 How This Works in D365FO

## 🧾 Every Transaction Posts to the Ledger

ERP systems do not “store business events” — they store **financial impact**

---

## 📦 Example – Purchase Transaction

| Step | Impact |
|-----|-------|
| Product receipt | Inventory ↑ (Asset) |
| Invoice | Payables ↑ (Liability) |

---

## 🛒 Example – Sales Transaction

| Step | Impact |
|-----|-------|
| Invoice | Revenue ↑ (P&L) |
| Cost of goods | Expense ↑ (P&L) |
| Customer balance | Asset ↑ (Balance Sheet) |

---

# 🧠 Consultant Insight

As a D365FO functional consultant, you must:

- Understand **financial impact of every action**
- Design:
  - Chart of Accounts
  - Financial dimensions
- Translate business processes into accounting logic

---

## ⚠️ Common Beginner Mistakes

- Treating ERP as just a system
- Confusing P&L with Balance Sheet
- Overloading Chart of Accounts instead of using dimensions

---

# ✅ Key Takeaways

- Balance Sheet = Financial position  
- Profit & Loss = Financial performance  
- Every ERP transaction has accounting impact  
- Understanding accounting = essential for ERP design  
