<div align="center">

<img width="162" height="157" alt="image" src="https://github.com/user-attachments/assets/3c5b7dc0-7c93-4b9f-856a-3a5701961eb1" />

# FairPay

### OCR + AI Powered Smart Bill Analysis

Know if you're paying a fair price.

Upload any bill or receipt, and FairPay will scan it using OCR technology, match products against a cloud database containing **30,000+ grocery products**, and instantly identify whether you're being overcharged.

---

### ⚡ Built With

Python • Flask • EasyOCR • PostgreSQL • RapidFuzz • Cloud Database

---

**Developed by Darshil Sharma**

</div>

---

# 📖 Overview

FairPay is an intelligent bill analysis platform designed to bring transparency to everyday purchases.

Using OCR technology, fuzzy product matching, and cloud-powered market pricing data, FairPay analyzes receipts and helps users determine whether they are paying a fair market price.

The platform processes bills, identifies products, compares prices against real-world market data, and generates actionable insights within seconds.

---

# 📸 Screenshots

<div align="center">

<img width="1835" height="921" alt="image" src="https://github.com/user-attachments/assets/e3cb2980-1909-4532-8811-c0e374da2984" />
---

# ✨ Features

### 📄 OCR Receipt Scanning

Extracts bill and receipt information directly from uploaded images.

### 🔍 Intelligent Product Matching

Uses RapidFuzz algorithms to identify products even when OCR output contains errors.

### ☁️ Cloud Market Database

Checks product prices against a cloud-hosted database containing over **30,000+ grocery products**.

### 💰 Smart Price Analysis

Automatically classifies purchases as:

- ✅ Fair Price
- ⚠️ Overpriced
- 📉 Underpriced
- ❓ No Match Found

### 📊 Bill History Tracking

Stores analyzed bills and transaction records for future reference.

### 🚀 Fast Processing

Provides pricing insights within seconds.

---

# ⚙️ How It Works

```text
Upload Bill
     ↓
OCR Text Extraction
     ↓
Product Detection
     ↓
Fuzzy Matching Engine
     ↓
Cloud Database Lookup
     ↓
Market Price Comparison
     ↓
Fair / Overpriced / Underpriced
```

---

# 🛠 Technology Stack

| Category | Technology |
|-----------|-----------|
| Backend | Python, Flask |
| OCR Engine | EasyOCR |
| Product Matching | RapidFuzz |
| Database | PostgreSQL |
| Cloud Infrastructure | Managed Cloud Database |
| Frontend | HTML5, CSS3, Jinja |
| ORM | SQLAlchemy |
| Deployment | Cloud Hosted |

---

# 📂 Project Structure

```text
FairPay/
│
├── screenshots/
│   ├── banner.png
│   ├── home.png
│   ├── review.png
│   ├── result.png
│   └── mobile.png
│
├── static/
│   └── ZeeResizer.ico
│
├── templates/
│   ├── main_page.html
│   ├── review.html
│   └── result.html
│
├── main.py
├── setup_db.py
├── migrate_products.py
├── migrate_transactions.py
├── test_db.py
│
├── .env
├── .gitignore
└── README.md
```

---

# 🚀 Core Technologies

- EasyOCR for bill scanning
- RapidFuzz for intelligent matching
- PostgreSQL cloud database
- SQLAlchemy ORM
- Flask backend architecture
- Session-based processing workflow
- Secure environment variable management

---

# 💡 Why FairPay?

Consumers often have no reliable way to determine whether they are paying a fair price for products.

FairPay solves this problem by combining OCR, cloud-scale product intelligence, and automated market-price comparison into a single seamless experience.

The platform empowers users to make informed purchasing decisions while promoting pricing transparency.

---

# 🔒 Proprietary Software Notice

© Darshil Sharma. All Rights Reserved.

This project is proprietary software.

The source code, database architecture, pricing datasets, matching algorithms, OCR workflow, business logic, and all associated intellectual property are owned exclusively by Darshil Sharma.

No part of this repository may be copied, modified, redistributed, reverse-engineered, or used commercially without prior written permission from the author.

This repository is published solely for portfolio and demonstration purposes.

---

# 👨‍💻 Developer

## Darshil Sharma

Python Full-Stack Developer • AI Enthusiast • Software Engineer

Building practical software solutions through automation, cloud technologies, and intelligent systems.

---

<div align="center">

### Scan • Compare • Verify

**FairPay — Smart Pricing Transparency Through Technology**

Made with ❤️ in India 🇮🇳

</div>
