# 🎉 Event Management System (EMS)

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</p>

> **A streamlined, full-stack platform designed to revolutionize how events are organized, managed, and experienced.**

## 📖 Overview

The **Event Management System (EMS)** is a robust web application built to simplify event organization. The platform provides a seamless experience for three distinct user types: Administrators, Organizers, and general Users. Through a modern, responsive, and animated UI, EMS allows for efficient event creation, category management, and ticket exploration.

This project was developed to master full-stack web development architecture, focusing on frontend-backend integration, RESTful APIs, relational database management, and secure authentication.

---

## ✨ Core Features

### 🛡️ Admin Portal
* **User Management:** Oversee and manage organizer and user accounts.
* **Global Monitoring:** Track platform-wide event activities and statuses.
* **Category Control:** Dynamically manage event categories and tags.
* **Analytics Dashboard:** Get a bird's-eye view of platform data and operations.

### 🎭 Organizer Dashboard
* **Event Creation:** Seamlessly draft, publish, and manage events.
* **Media Management:** Upload and manage high-quality event images.
* **Logistics Tracking:** Define event schedules, timings, and venues.
* **Live Updates:** Edit event details on the fly.

### 🎟️ User Experience
* **Discovery Hub:** Browse a dynamic feed of upcoming events.
* **Smart Search:** Filter events by category, title, or date.
* **Event Details:** View comprehensive information about venues and schedules.
* **Responsive UI:** Smooth browsing experience across all devices.

---

## 🛠️ Technical Stack

* **Frontend:** React.js, JavaScript, HTML5, CSS3, Axios, Framer Motion (for fluid animations)
* **Backend:** PHP (RESTful API Architecture)
* **Database:** MySQL

---

## 📂 Project Structure

```bash
EMS/
│
├── backend/            # PHP API endpoints and core logic
│   ├── Admin/          # Admin-specific controllers
│   ├── Organizer/      # Organizer-specific controllers
│   ├── config/         # Database connections and configs
│   └── APIs/           # General routing and endpoints
│
├── frontend/           # React application
│   ├── src/            # Main source code
│   ├── assets/         # Static files, images, and icons
│   ├── pages/          # React views (Home, Dashboard, etc.)
│   └── components/     # Reusable UI components
│
└── database/           # SQL migration files and schemas

---

# Installation

## Clone Repository

```bash
git clone https://github.com/Acharya-Arjun/Event-Management-System.git
```

## Move Project to XAMPP htdocs

```bash
C:/xampp/htdocs/
```

## Install Frontend Dependencies

```bash
npm install
```

## Start Services

Start the following services using XAMPP:

* Apache
* MySQL

## Import Database

1. Open phpMyAdmin
2. Create a database
3. Import the provided SQL file

## Run Frontend

```bash
npm run dev
```
# 📸 Interface Gallery

## 🛡️ Admin Portal

<table>
  <tr>
    <td width="50%"><img alt="Admin Dashboard 1" src="https://github.com/user-attachments/assets/be6706e6-da19-457d-a3b0-8ecd6e90315a" width="100%" /></td>
    <td width="50%"><img alt="Admin Dashboard 2" src="https://github.com/user-attachments/assets/65bc0973-43cf-42f7-a401-e1bc249497e9" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="Admin View 3" src="https://github.com/user-attachments/assets/dd8289a8-23a7-4f15-bd85-a7f8cef6a06c" width="100%" /></td>
    <td><img alt="Admin View 4" src="https://github.com/user-attachments/assets/6db5b4e0-bff7-4df9-871f-2643dd6d9658" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="Admin View 5" src="https://github.com/user-attachments/assets/511cd1f8-3115-4f4a-a24d-12ca015d1d99" width="100%" /></td>
    <td><img alt="Admin View 6" src="https://github.com/user-attachments/assets/58171424-6c76-4b46-ac37-2aa5df0def6f" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="Admin View 7" src="https://github.com/user-attachments/assets/586341a7-f017-4849-ac1d-54e0ecbd5357" width="100%" /></td>
    <td><img alt="Admin View 8" src="https://github.com/user-attachments/assets/8c4474ad-4a80-4ada-ba1d-e618b1e87a43" width="100%" /></td>
  </tr>
</table>

## 🎭 Organizer Dashboard

<table>
  <tr>
    <td width="50%"><img alt="Organizer View 1" src="https://github.com/user-attachments/assets/eb97efae-c12d-4681-8938-19a6736041ad" width="100%" /></td>
    <td width="50%"><img alt="Organizer View 2" src="https://github.com/user-attachments/assets/476313ad-e72a-4b41-bcb0-39240efa918d" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="Organizer View 3" src="https://github.com/user-attachments/assets/feb4ad24-ff08-491d-891a-e8eeef34835c" width="100%" /></td>
    <td><img alt="Organizer View 4" src="https://github.com/user-attachments/assets/24ef3984-9e5b-463b-865a-4e63f7b855e7" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="Organizer View 5" src="https://github.com/user-attachments/assets/4a589fc2-8cc8-41fd-979e-1537665827fa" width="100%" /></td>
    <td><img alt="Organizer View 6" src="https://github.com/user-attachments/assets/2ed14c2a-b4c4-4490-9d84-43314eead6bb" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="Organizer View 7" src="https://github.com/user-attachments/assets/6a6e0ef0-5c9e-4fab-9357-61c47a2a98bb" width="100%" /></td>
    <td><img alt="Organizer View 8" src="https://github.com/user-attachments/assets/23d22601-3b90-478d-b3b2-625b41e47349" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="Organizer View 9" src="https://github.com/user-attachments/assets/be4a879c-3140-4ade-b8db-5fe7ed96596b" width="100%" /></td>
    <td></td> </tr>
</table>

## 🎟️ User Experience

<table>
  <tr>
    <td width="50%"><img alt="User View 1" src="https://github.com/user-attachments/assets/0689b769-4de3-45d1-a4ed-83d1e2d0c53d" width="100%" /></td>
    <td width="50%"><img alt="User View 2" src="https://github.com/user-attachments/assets/67045b7e-e510-4f03-8ca2-3b1055dcba5b" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="User View 3" src="https://github.com/user-attachments/assets/4513393b-c362-4d3f-933a-808aba813c67" width="100%" /></td>
    <td><img alt="User View 4" src="https://github.com/user-attachments/assets/c8c1a48c-9f52-43d6-9e6c-0052343557dc" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="User View 5" src="https://github.com/user-attachments/assets/5aee560d-a701-49cf-ad78-e469eab6821e" width="100%" /></td>
    <td><img alt="User View 6" src="https://github.com/user-attachments/assets/eef4ea20-e1d4-4049-8b79-4c1f18d4d275" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="User View 7" src="https://github.com/user-attachments/assets/d69ea530-5180-44d5-a979-7754f408d587" width="100%" /></td>
    <td><img alt="User View 8" src="https://github.com/user-attachments/assets/4fd505c2-da91-4d44-8fac-de39668f3877" width="100%" /></td>
  </tr>
  <tr>
    <td><img alt="User View 9" src="https://github.com/user-attachments/assets/11119c1f-0fd0-41f4-a84f-6a1a00f12aa5" width="100%" /></td>
    <td><img alt="User View 10" src="https://github.com/user-attachments/assets/0d359ed6-4a6e-4219-8133-613fa57ce064" width="100%" /></td>
  </tr>
</table>

---

---

# 🔮 Future Roadmap

* 💳 Payment Integration: Secure online ticket booking and checkout.

* 🤖 Smart Recommendations: AI-driven event suggestions based on user behavior.

* 📧 Automated Notifications: Email and SMS alerts for event updates.

* 📱 PWA Support: Enhancing mobile responsiveness and offline capabilities.

*📡 WebSockets: Real-time event capacity updates and live chat.

---

# 🎓 Learning Outcomes

Developing this project solidified my skills in:

* 🌐 Architecting Full-Stack Web Applications

* ⚛️ Building dynamic, stateful UIs with React.js & Framer Motion

* 🔌 Integrating backend PHP logic with RESTful API principles

* 🗃️ Designing normalized relational databases using MySQL

* 🔐 Implementing secure user authentication and role-based authorization

---

# 👨‍💻 Author

Arjun Acharya

🔗 GitHub: https://github.com/Acharya-Arjun
---

# 📜 License

📝 This project was developed for academic and learning purposes.
