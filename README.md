# 🔐 PasswordStore Smart Contract Audit  

![Status](https://img.shields.io/badge/Audit-Completed-brightgreen?style=for-the-badge)  
![Severity](https://img.shields.io/badge/Findings-2_High_1_Info-orange?style=for-the-badge)  
![Tool](https://img.shields.io/badge/Tool-Foundry-blue?style=for-the-badge)  
![Language](https://img.shields.io/badge/Solidity-%5E0.8.0-lightgrey?style=for-the-badge)

---

## 🧾 Overview  

This repository contains a **security audit** of the `PasswordStore` smart contract.  
The goal was to identify security vulnerabilities, logical flaws, and potential improvements in code quality.

---
## 🔗 Original Contract

The audited contract is based on the **PasswordStore** example from Patrick Collins' [Cyfrin Updraft Course](https://github.com/Cyfrin/3-passwordstore-audit/tree/onboarded)

---

## 📊 Audit Summary  

| **Severity** | **Count** | **Description** |
|---------------|------------|------------------|
| 🔴 **High** | 2 | Critical security flaws affecting contract functionality. |
| ⚪ **Informational** | 1 | Minor issue or documentation inconsistency. |

---

## 🚨 Key Findings  

| ID | Title | Severity |
|----|--------|-----------|
| [H-1] | Password stored on-chain (publicly visible) | 🔴 High |
| [H-2] | Missing access control in `setPassword()` | 🔴 High |
| [I-1] | Incorrect NatSpec documentation | ⚪ Informational |


## 🧰 Tools & Environment  
- 🧪 **Foundry** – Contract testing and local deployment  
- 🧮 **Cast CLI** – Storage inspection and decoding  
- 📈 **Solidity Metrics** – Code complexity and size analysis  
- 📊 **CLOC** – Lines of code and comment ratio  

---

## 👨‍💻 Auditor  

**Name:** Vaishno Raj  
**Role:** Smart Contract Security Auditor  
**Focus:** Solidity • Foundry • Web3 Security • Audit Competitions  

🔗 *Building secure, transparent, and efficient blockchain systems.*

---

## ⭐ Support  

If you found this helpful, consider giving the repo a ⭐ to support my work!  
Let's make Web3 more secure together 💪  
