# 🔐 Command-Line Password Manager — Secure Python CLI App

A secure and lightweight **command-line password manager** built in Python. It allows you to **store, retrieve, and manage encrypted passwords locally**, protected by a **master password**. The application uses **AES encryption via Fernet** from the `cryptography` library, ensuring your credentials stay private and secure.

---

## ✨ Features

- 🔑 **Master password authentication** to unlock your vault
- 🔒 **AES encryption** using `cryptography.Fernet` for all credentials
- 🗂️ **Store multiple site/app credentials** (username + password)
- 🧠 View saved credentials **only after successful login**
- 🧾 Data stored in a **local encrypted JSON vault**
- 💼 Fully **offline**, **portable**, and **easy to use**

---

## 💻 Technologies Used

- **Python 3.x**
- [`cryptography`](https://pypi.org/project/cryptography/) — for AES encryption (Fernet)
- `getpass` — for hidden password input
- `json` — for encrypted data storage

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cli-password-manager.git
cd cli-password-manager
