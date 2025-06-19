# Buyzo 🛍️ – Cloud-Based E-Commerce Platform

**Buyzo** is a scalable, cloud-based e-commerce platform built with **PrestaShop** and deployed on **Google Cloud Platform (GCP)**. It utilizes a load-balanced infrastructure to provide reliability, performance, and future-ready scalability.

## 🔗 Live Demo
🛒 Visit the store:  
👉 [http://34.60.221.65/index.php](http://34.60.221.65/index.php)

📽️ Watch the walkthrough video:  
👉 [Project Demo on YouTube](https://youtu.be/epyUcH8FShc)

---

## ⚙️ Technologies Used

- 🛒 **PrestaShop** – open-source e-commerce system
- ☁️ **Google Cloud Compute Engine** – virtual machines
- 🌐 **Google Cloud Load Balancer** – HTTP(S) traffic distribution
- 🐬 **MariaDB** – lightweight and powerful database backend
- 🐧 **Debian Linux** – server operating system
- 🔧 **Apache2**, **PHP** – web server stack
- 🔒 **Firewall Rules** – to manage HTTP/HTTPS access

---

## 🚀 Features

- ✅ Fully deployed on GCP
- 🔄 Auto-scalable setup via instance group and load balancer
- 🧩 Modular and customizable e-commerce platform (PrestaShop)
- 🧱 Open-source components
- 🌍 Public access via static IP
- 🛠️ Ready for further domain integration and HTTPS

---

## 📦 Installation Summary

1. Upload PrestaShop files to VM (`/var/www/html`)
2. Install Apache, PHP, and MariaDB on Debian
3. Create database and PrestaShop admin user
4. Set up firewall rules for HTTP (port 80)
5. Deploy Google Cloud Load Balancer and add backend instance group

---

## 📁 VM Directory Overview

```bash
/var/www/html/        # Web root directory
├── index.php         # PrestaShop entry point
├── admin/            # Admin panel
└── ...               # Other core PrestaShop files
