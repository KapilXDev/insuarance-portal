# 🛡️ Insurance Portal

A full-stack web platform to streamline insurance policy purchases, premium calculations, KYC management, and real-time verification using microservices.

---

## 🚀 Features

- 🧾 Create, view, and manage insurance policies
- 💳 Premium calculation based on user profile
- 🔐 KYC verification with real-time third-party integration
- 📈 Admin dashboard for claims and user analytics

---

## ⚙️ Tech Stack

| Layer        | Tech                          |
|--------------|-------------------------------|
| Frontend     | React.js + Tailwind + Redux   |
| Backend      | Spring Boot / Nest.js         |
| DB & Caching | PostgreSQL, Redis             |
| Auth & APIs  | JWT, REST/GraphQL             |
| Infra        | Docker, AWS (EC2/S3), Render  |

---

## 📦 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/KapilXDev/insurance-portal.git

# Backend setup (Spring Boot)
cd backend
./gradlew bootRun

# Frontend setup (React)
cd frontend
npm install
npm start
