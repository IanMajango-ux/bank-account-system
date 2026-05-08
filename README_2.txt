# 🏦 Python OOP Bank Account System

A modular, object-oriented bank account management system built in Python.  
Designed to demonstrate core OOP principles: **encapsulation, inheritance, polymorphism, and composition**.

---

## 📁 Project Structure

```
bank_system/
│
├── bank/
│   ├── __init__.py          # Package exports
│   ├── account.py           # Base Account class (encapsulation, abstraction)
│   ├── account_types.py     # SavingsAccount, CurrentAccount, FixedDepositAccount (inheritance)
│   └── bank.py              # Bank class — manages all accounts (composition)
│
└── main.py                  # Demo simulation — run this to see it in action
```

---

## ⚙️ OOP Concepts Demonstrated

| Concept | Where |
|---|---|
| **Encapsulation** | Private attributes (`_balance`, `_transactions`) with public properties |
| **Inheritance** | `SavingsAccount`, `CurrentAccount`, `FixedDepositAccount` extend `Account` |
| **Polymorphism** | Each subclass overrides `withdraw()` with its own rules |
| **Composition** | `Bank` class manages a collection of `Account` objects |
| **Abstraction** | `Account` defines shared interface; subclasses handle specifics |
| **Custom Exceptions** | `InsufficientFundsError` for clean error handling |

---

## 🏧 Account Types

### Savings Account
- Earns **3.5% monthly interest**
- Enforces a **KES 1,000 minimum balance**

### Current Account
- Supports **KES 10,000 overdraft**
- Charges a **KES 50 withdrawal fee** per transaction

### Fixed Deposit Account
- Funds **locked for a set term** (no withdrawals until maturity)
- Interest rates: **5% (< 6 months)**, **7% (6–11 months)**, **10% (12+ months)**


python main.py
```
---

##
══════════════════════════════════════════════════
   PYTHON OOP BANK ACCOUNT SYSTEM
   by Ian Alfred Majango
══════════════════════════════════════════════════

   New Savings Account opened for Ian Majango | A/C No: 1001
   New Current Account opened for Bob Otieno  | A/C No: 1003
   Transferred KES 5,000.00 from A/C 1003 → A/C 1001
   Interest applied to 2 savings account(s).

---

##

**Ian Alfred Majango**  
BSc Information & Cybersecurity — Riara University  
GitHub: [github.com/ianmajango-ux](https://github.com/ianmajango-ux)

