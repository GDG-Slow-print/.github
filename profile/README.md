# 🌱 Sustainable Travel Platform

A web platform designed to promote **sustainable travel**, **revitalize local businesses**, and **encourage eco-friendly behavior** through carbon mileage rewards and community-based exchanges.

---
## 🎯 Project Purpose

The **Sustainable Travel Platform** aims to create a positive feedback loop between **eco-friendly travel behavior**, **local community revitalization**, and **personal rewards**.  
Through tracking carbon-reducing activities and offering meaningful benefits—such as free lodging or meals in exchange for local contributions—the platform turns everyday travel into a sustainable and community-driven experience.

> “Travel that helps the planet, supports locals, and rewards you.”



## 🧩 Key Features

### 👤 User Management
- Sign up / Login / Logout
- JWT-based authentication
- Password encryption and (upcoming) reset via email

### 🌿 Carbon Footprint Tracking
- Record eco-friendly transport use (walking, bicycle, subway, etc.)
- Earn carbon mileage points
- View user ranking based on mileage

### 🏡 Lodging Promotion Match
- Travelers promote local accommodations through SNS
- In return, hosts offer free lodging – a win-win exchange model

### 🤝 Local Help Exchange
- Local residents post help requests (e.g., harvest, bike rental)
- Travelers volunteer and receive free meals or lodging in return

### 🤖 AI Recommendations (via Gemini API - Planned)
- AI-powered suggestions for challenges, locations, and activities

---

## 🏗️ Tech Stack

### 🖥️ Frontend
- React 
- Zustand
- TailwindCSS 

### 📦 Backend
- Java 21
- Spring Boot
- Spring Security (JWT)
- AWS EC2
- MySQL
- Gradle
- Gemini

### 🔐 Security
- JWT Token Authentication
- PBKDF2 with SHA-512 for password encryption

### ☁️ External APIs (Planned)
- Google Gemini API (AI Chatbot)
- Local business APIs for coupons and discounts

---
## 🖼️ Wireframe Preview

![Wireframe](./와이어프레임.svg)

---

## 🔮 Future Development

-  Add challenge & eco-action verification features
-  Integrate carbon mileage with local business partnerships
-  Implement password reset via email
-  Fix remaining bugs related to authentication and session handling
