# 💬 NGOBROLIN – REAL-TIME CHAT APPLICATION

**Ngobrolin** adalah aplikasi **mobile real-time chat** yang memungkinkan pengguna untuk berkomunikasi secara langsung melalui pesan pribadi.

Aplikasi ini dibangun menggunakan **Flutter** pada sisi mobile dan **Node.js (Express.js)** pada sisi backend dengan **PostgreSQL** sebagai database. Sistem komunikasi real-time diimplementasikan menggunakan **WebSocket melalui Socket.io**, sehingga pesan dapat dikirim dan diterima secara instan antar pengguna.

---

## 👨‍💻 Maintainer

Project ini dikembangkan oleh:

**Yudha Haryoputranto**  
GitHub: https://github.com/yudhah52

---

## ✨ FITUR UTAMA

### 🔐 User Authentication

- Registrasi dan login pengguna
- Manajemen akun pengguna secara aman
- Password disimpan menggunakan **Bcrypt hashing**

### 💬 Real-time Messaging

- Pengiriman pesan secara **instan**
- Komunikasi **real-time menggunakan WebSocket (Socket.io)**
- Sinkronisasi pesan antar pengguna

### 🔔 Notification System

- Notifikasi pesan masuk menggunakan **Firebase Cloud Messaging (FCM)**
- Pengguna tetap menerima notifikasi meskipun aplikasi sedang tidak aktif

### 👥 User Interaction

- **Private chat** antar pengguna
- **User search** untuk menemukan pengguna lain
- **Private account settings**
- **Blocked user management**
- **Language settings (Indonesia / English)**

---

## 🧱 TECH STACK

| Layer / Komponen           | Teknologi yang Digunakan |
|---------------------------|--------------------------|
| **Mobile Application**    | Flutter |
| **Arsitektur Aplikasi**   | MVVM (Model–View–ViewModel) |
| **State Management**      | Provider |
| **Backend API**           | Node.js, Express.js |
| **Realtime Communication**| WebSocket (Socket.io) |
| **Database**              | PostgreSQL |
| **Push Notification**     | Firebase Cloud Messaging |

---

## ⚙️ SYSTEM ARCHITECTURE

Sistem **Ngobrolin** menggunakan arsitektur full-stack yang terdiri dari beberapa komponen utama:
```
Mobile Application
Flutter + Provider
⬇
Realtime Communication
WebSocket (Socket.io)
⬇
Backend API
Node.js + Express.js
⬇
Database
PostgreSQL
⬇
Notification Service
Firebase Cloud Messaging (FCM)
```
Arsitektur ini memungkinkan komunikasi pesan secara **real-time**, pengelolaan data pengguna, serta pengiriman notifikasi secara efisien.

---

## 👨‍💻 MY CONTRIBUTIONS

Pada proyek ini saya bertanggung jawab untuk:

- Merancang dan mengembangkan aplikasi **Ngobrolin** sebagai **real-time chat application** menggunakan **Flutter** dan **Node.js**.
- Mengimplementasikan **WebSocket (Socket.io)** untuk komunikasi pesan secara real-time.
- Mengintegrasikan **Firebase Cloud Messaging (FCM)** untuk sistem notifikasi pesan.
- Mengimplementasikan **Bcrypt hashing** untuk keamanan autentikasi pengguna.
- Mengembangkan berbagai fitur utama seperti **private chat, user search, private account, blocked user, dan pengaturan bahasa (ID/EN)**.
- Mendesain serta mengembangkan **relational database schema** menggunakan **PostgreSQL**.

---

## 📄 DOKUMENTASI

Dokumentasi tambahan mengenai desain antarmuka dapat dilihat pada tautan berikut:

**Figma UI Design**  
https://www.figma.com/design/dslLxMk9eGFG3uv0J60n8R/Ngobrolin?node-id=0-1&t=8zEPpILNlElecNqd-1

---

## 🔗 REPOSITORY

Source code proyek dapat dilihat pada repository berikut:

**GitHub Repository**  
https://github.com/Ngobrolin-App
