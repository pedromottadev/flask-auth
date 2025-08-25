# 🔏 flask auth project

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Flask-2.3.0-black?style=for-the-badge&logo=flask" />
  <img src="https://img.shields.io/badge/SQLAlchemy-3.1.1-red?style=for-the-badge&logo=sqlite" />
</p>

---

## 📖 Overview

This project is a **Flask-based web application** built with a modular and scalable architecture.  
It integrates **Flask-SQLAlchemy** for database management, **Flask-Login** for authentication, and **PyMySQL** as a MySQL driver.  

The goal is to provide a **secure, lightweight, and customizable application boilerplate** for developers who want to build modern Python web applications.

---

## ⚡ Features

- 🔐 **User Authentication** (Flask-Login)  
- 🗄 **Database Integration** (SQLAlchemy + PyMySQL)  
- 🔑 **Secure Password Hashing** (bcrypt + cryptography)  
- 🛠 **Clean and Modular Project Structure**  
- 🚀 **Ready for Deployment**  

---

## 🛠 Tech Stack

- **Backend:** Flask (Python)  
- **Database ORM:** SQLAlchemy  
- **Authentication:** Flask-Login  
- **Database Driver:** PyMySQL  
- **Security:** bcrypt, cryptography  
- **WSGI:** Werkzeug  

---

## 📦 Requirements

All dependencies are pinned to specific versions for maximum stability:  

```txt
Flask==2.3.0
Flask-SQLAlchemy==3.1.1
Flask-Login==0.6.2
werkzeug==2.3.0
pymysql==1.1.0
cryptography==41.0.7
bcrypt