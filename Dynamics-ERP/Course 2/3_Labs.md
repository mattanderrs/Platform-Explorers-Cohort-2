# Lab 02 – General Ledger & Financial Structure Setup

## Objective
To configure and understand the foundational components of the General Ledger in D365FO.

Focus is on:
- Structure
- Design decisions
- Financial logic

---

## Scenario

You are continuing your role as a functional consultant for BlueContoso.

The company now requires:
- A working Chart of Accounts
- Financial dimensions for reporting
- Basic ledger configuration

---

## Prerequisites
- Completed Week 01 setup
- Legal entity already created
- Access to General Ledger module

---

## Task 1 – Design Chart of Accounts (Conceptual)

Before system entry, define:
- Number of accounts required
- Categories:
  - Assets
  - Liabilities
  - Revenue
  - Expenses

✅ Document your design BEFORE creating anything

---

## Task 2 – Create Chart of Accounts (System)

1. Define Chart of Accounts
2. Create main accounts:
   - Cash
   - Payables
   - Receivables
   - Revenue
   - Cost of Goods Sold
   - Expenses

---

## Task 3 – Configure Financial Dimensions

1. Create dimension: Department
2. Create dimension: Cost Center
3. Assign values to each

---

## Task 4 – Assign Ledger Setup

1. Link Chart of Accounts to legal entity
2. Assign:
   - Accounting currency: EUR
   - Fiscal calendar (from Week 1)

---

## Task 5 – Basic Journal Posting

1. Create a general journal
2. Post a simple transaction:
   - Expense entry
   - Revenue entry

---

## Validation Checklist

- Chart of Accounts created correctly
- Main accounts categorized properly
- Financial dimensions active
- Ledger configured
- Journal posted successfully

---

## Reflection Questions

- Which matters more: COA or dimensions?
- What happens if too many accounts are created?
- What happens if too few dimensions are created?
