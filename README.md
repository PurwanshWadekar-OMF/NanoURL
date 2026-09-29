# NanoURL 🚀

A full-stack, production-oriented URL shortening platform built with **Spring Boot** and **React**.

NanoURL allows users to create short URLs, manage their links, track click analytics, use custom aliases, and secure their accounts with JWT authentication.

---

## ✨ Features

- 🔗 Create short URLs from long URLs
- 🎯 Custom URL aliases
- ⏳ Link expiration
- 🔐 JWT-based authentication
- 👤 User registration and login
- 📊 Click analytics
- ⚡ Redis caching for frequently accessed URLs
- 🛡️ Rate limiting
- 📱 Responsive React frontend
- 🐳 Docker-ready backend
- 📡 RESTful APIs
- 🗄️ Persistent data storage with relational database

---

## 🏗️ Project Structure

```text
NanoURL/
│
├── url-shortener-react/       # React frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .gitignore
│
├── url-shortener-sb/          # Spring Boot backend
│   ├── src/
│   ├── pom.xml
│   └── .gitignore
│
└── README.md
