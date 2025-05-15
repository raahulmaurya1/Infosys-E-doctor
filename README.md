# 🏥 Outpatient Doctor Appointment System

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Tech Stack](https://img.shields.io/badge/Tech%20Stack-React%2C%20SpringBoot%2C%20MySQL-blue)

A full-stack web application that streamlines the outpatient appointment process by enabling patients to book appointments with doctors based on real-time availability. It includes secure authentication, automated notifications, admin dashboards, and chatbot support for FAQs.

---

## ✨ Overview

- **🎯 Title:** Outpatient Doctor Appointment System  
- **📄 Description:** A modern, responsive web app for managing outpatient doctor appointments. It connects patients and doctors with real-time availability, automated scheduling, and secure patient information handling.

---

## 🚀 Features

✅ **User Authentication**  
&emsp;Secure login, registration, email verification, and user profile management.

✅ **Doctor Availability**  
&emsp;Doctors can set/manage availability; patients book accordingly.

✅ **Smart Appointment Scheduling**  
&emsp;Includes slot selection, real-time tracking, and a chatbot for FAQs.

✅ **Integrated Appointment Management**  
&emsp;View, manage, and cancel appointments with notifications and payment support.

✅ **Patient Medical Records**  
&emsp;Secure storage of personal and recovery data with downloadable bills.

✅ **Notification System**  
&emsp;Email and SMS reminders for upcoming appointments and changes.

✅ **Admin Dashboard**  
&emsp;View reports and manage users, doctors, and appointments efficiently.

✅ **Chatbot Integration**  
&emsp;AI-based FAQ chatbot to assist users instantly.

---

## 🛠️ Tech Stack

| Layer      | Technologies Used                                                                 |
|------------|-------------------------------------------------------------------------------------|
| Frontend   | HTML, CSS, JavaScript, **React.js**, `react-chartjs-2`, **React ChatBotify**       |
| Backend    | **Spring Boot**, RESTful APIs                                                      |
| Database   | **MySQL**                                                                          |
| Testing    | **Mockito**                                                                        |
| Notifications | **JavaMailSender**, optional SMS gateway integration                           |
| Others     | JSON Web Tokens (JWT), Bcrypt for password encryption                             |

---

## 🖥️ Screenshots

> Add screenshots or a demo GIF here if available for visual reference.

<p align="center">
  <img src="https://via.placeholder.com/600x300?text=Login+Screen" alt="Login UI" />
  <img src="https://via.placeholder.com/600x300?text=Dashboard" alt="Dashboard" />
</p>

---

## ⚙️ Setup Instructions

### 🧾 Prerequisites

- Node.js and npm
- Maven
- MySQL server
- JDK 11+

---

### 🔧 Installation Steps

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/outpatient-appointment-system.git
cd outpatient-appointment-system
```

#### 2️⃣ Backend Setup (Spring Boot)

```bash
cd backend
mvn install
```

- Configure `application.properties` with your DB credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=root
spring.datasource.password=your_password
```

- Run the server:

```bash
mvn spring-boot:run
```

#### 3️⃣ Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

---

## 🧪 Testing

- **Unit Tests:** Run with Mockito
```bash
mvn test
```

---

## 📬 Contact

📧 **Email:** [raahulmaurya2@gmail.com](mailto:raahulmaurya2@gmail.com)  

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---

⭐ *Feel free to fork this repo, submit issues, or make pull requests to enhance it further!*
