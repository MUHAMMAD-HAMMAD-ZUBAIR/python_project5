# 🔐✨ Secure Vault – Your Personal Encrypted Secret Keeper

Welcome to **Secure Vault**, a powerful and elegant Streamlit-based password manager that securely stores your secrets using **Fernet encryption** and a **multi-user login system**. Everything is designed with love ❤️ and security 🔐 in mind.

🧑‍💻 Developed with care by: **MUHAMMAD HAMMAD ZUBAIR**  
🌐 Live App: [👉 Try Secure Vault](https://secure-databymhz.streamlit.app/)

---

## 📚 Table of Contents

- 🚀 [Features](#-features)  
- 💻 [Live Demo](#-live-demo)  
- 🖼️ [Screenshots](#-screenshots)  
- 🔧 [How It Works](#-how-it-works)  
- 📦 [Installation](#-installation)  
- 🛠️ [Tech Stack](#-tech-stack)  
- 🛡️ [Security Overview](#-security-overview)  
- 📁 [File Structure](#-file-structure)  
- 🌱 [Future Enhancements](#-future-enhancements)  
- 🙋‍♂️ [About the Developer](#-about-the-developer)  
- 📜 [License](#-license)

---

## 🚀 Features

🎯 **User Registration & Login** – Secure access with hashed passkeys  
🔐 **Fernet Encryption** – All secrets are safely encrypted  
🗂️ **Label + Secret Input** – Tag your secrets for easy identification  
📥 **Save, View & Delete Secrets** – Full control over your data  
🕒 **Timestamped History** – Track when you saved your secrets  
👥 **Multi-User Support** – Each user has their own secure vault  
🎨 **Animated UI** – Stylish, interactive Lottie animations  
🌑 **Dark Mode Friendly UI** – Eye-comfort focused design  
🚀 **Streamlit Cloud Deployable** – Ready for online access  
✅ **Responsive Design** – Works on mobile & desktop

---

## 💻 Live Demo

🔗 Click to explore:  
**[🌐 https://secure-databymhz.streamlit.app/](https://secure-databymhz.streamlit.app/)**

No installation required — just register and start encrypting! 🔒

---

## 🔧 How It Works

1. 📝 Register with your username and secure passkey  
2. 🧠 Login with the same passkey (SHA-256 hashed)  
3. 🔐 Add your secret and label — it gets encrypted  
4. 🗂️ View or delete your secrets anytime  
5. 🧾 Track activities with built-in history log

All data is stored **per-user**, so your secrets are never mixed.

---

## 📦 Installation

### 🔍 Requirements

- ✅ Python 3.7+
- ✅ Pip installed

### ⚙️ Steps to Run

```bash
# 1. Clone this repository
git clone https://github.com/your-username/secure-vault.git
cd secure-vault

# 2. Install the dependencies
pip install -r requirements.txt

# 3. Run the Streamlit app
streamlit run secure_vault_app.py
```

✅ That’s it! Your Secure Vault is now running locally.

---

## 🛠️ Tech Stack

| Area         | Tool/Library              |
|--------------|---------------------------|
| 🖥️ Frontend   | Streamlit, Lottie, CSS     |
| 🔐 Encryption | `cryptography.fernet`     |
| 🔑 Hashing    | SHA-256 (`hashlib`)        |
| 💾 Storage    | JSON (persistent file)    |
| ☁️ Deploy     | Streamlit Cloud           |

---

## 🛡️ Security Overview

🔒 **Passkeys are never stored** — only SHA-256 hashes  
🔐 **Secrets are encrypted** before saving  
👥 **Users can only see their own secrets**  
🧠 All data stored in an encrypted format  
⚠️ No secret is visible in plaintext unless decrypted in-app

---

## 📁 File Structure

```
secure_vault_app.py     # 🎯 Main application logic
data.json               # 💾 Encrypted user secrets storage
requirements.txt        # 📦 Required dependencies
README.md               # 📘 This documentation
```

---

## 🌱 Future Enhancements

📌 Password Change/Reset  
📌 Admin Dashboard  
📌 Cloud Database Support (e.g., Firebase, MongoDB)  
📌 Two-Factor Authentication  
📌 Secret Export/Download Feature  
📌 Custom Dark/Light Themes  

---

## 🙋‍♂️ About the Developer

🧑‍💻 **MUHAMMAD HAMMAD ZUBAIR**  
🌟 Passionate about software engineering, cloud AI, and secure systems  
🛠️ Always learning, always building  
📫 Reach out for collaborations or feedback

---

## 📜 License

This project is licensed under the **MIT License**.  
Use it freely and responsibly — give credit where due! 🙌

---

> 💬 "Your secrets matter. Protect them with Secure Vault."  
> — *MUHAMMAD HAMAD ZUBAIR*
