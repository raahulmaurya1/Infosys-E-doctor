# 🏥 E-Doctor - Outpatient Medical Appointment Management System

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Tech Stack](https://img.shields.io/badge/Tech%20Stack-React%2C%20SpringBoot%2C%20MySQL-blue)

A full-stack web application built with **Spring Boot** and **React.js**, designed to streamline outpatient appointment scheduling, communication, and healthcare management. It provides dedicated interfaces for **patients**, **doctors**, and **administrators**, offering secure authentication, payment processing, AI chatbot assistance, and real-time updates.

---

## ✨ Overview

- **🎯 Title:** E-Doctor - Outpatient Doctor Appointment System  
- **📄 Description:** A modern and responsive platform for managing outpatient doctor appointments. Features include real-time doctor availability, patient records, appointment scheduling, and a comprehensive dashboard system.

---

## 🚀 Key Features

### 🧑‍⚕️ For Patients
- Account creation, login, and password reset via email OTP
- Doctor search and booking by availability
- Appointment tracking and cancellation
- Feedback submission
- Secure payment integration using Stripe
- Medical history and downloadable bills
- Email & SMS notifications

### 👨‍⚕️ For Doctors
- Profile and availability management
- Appointment tracking and updates
- Access to patient medical history
- Email alerts on appointment changes

### 🛠️ For Admins
- Manage users (patients & doctors)
- Monitor all appointments and statistics
- System-wide availability and feedback management
- Admin dashboard for analytics

### 💬 Extras
- AI-powered FAQ chatbot
- Notification system with email & SMS
- Real-time updates and alerts

---

## 🧱 Tech Stack

| Layer      | Technologies Used                                                                 |
|------------|-------------------------------------------------------------------------------------|
| Frontend   | HTML, CSS, JavaScript, **React.js**, `react-chartjs-2`, **React ChatBotify**       |
| Backend    | **Spring Boot**, RESTful APIs                                                      |
| Database   | **MySQL**, JPA, Hibernate                                                          |
| Security   | **Spring Security**, BCrypt, JWT, CSRF                                             |
| Payments   | **Stripe API**                                                                     |
| Notifications | **JavaMailSender**, optional SMS integration                                   |
| Testing    | **Mockito**                                                                        |

---

## 📡 API Endpoints

### 🔐 User Management
- `POST /addUser` – Register user  
- `POST /loginUser` – Authenticate  
- `POST /forgot-password` – Password reset initiation  
- `POST /reset-password` – Complete password reset

### 👨‍⚕️ Doctor Management
- `POST /doctor/addDoctor`  
- `GET /doctor/getDoctor/{doctorId}`  
- `GET /doctor/getAllDoctors`  
- `PUT /doctor/updateDoctor`  
- `DELETE /doctor/deleteDoctor/{doctorId}`  

### 👥 Patient Management
- `POST /patient/addPatient`  
- `GET /patient/getPatient/{patientId}`  
- `GET /patient/getAllPatients`  
- `PUT /patient/updatePatient`  
- `DELETE /patient/deletePatient/{patientId}`  

### 📅 Appointment Management
- `GET/POST/PUT/DELETE /appointments`  
- `GET /appointments/doctor`  
- `GET /appointments/patient`  
- `GET /appointments/date`  

### ⭐ Feedback System
- `POST /feedback`  
- `GET /feedback/doctor/{doctorId}`  
- `GET /feedback/patient/{patientId}`  

### 💳 Payment Processing
- `POST /api/payment/create-checkout-session`  
- `GET /api/payment/success`  

---

## 🔐 Security Features

- Password encryption using **BCrypt**
- **JWT**-based secure authentication
- CSRF protection
- Role-based access control
- Email verification for password reset

---

## 🖼️ Screenshots (Placeholders)

> Replace with actual screenshots or demo GIFs

<p align="center">
  <img src="https://via.placeholder.com/600x300?text=Login+Screen" alt="Login UI" />
  <img src="https://via.placeholder.com/600x300?text=Dashboard" alt="Dashboard" />
</p>

---

## ⚙️ Setup Instructions

### 🧾 Prerequisites

- **Node.js** and **npm**
- **JDK 11+**
- **Maven**
- **MySQL server**
- **Stripe account** for payment integration

---

### 🔧 Installation Steps

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/e-doctor-appointment-system.git
cd e-doctor-appointment-system
```

#### 2️⃣ Backend Setup (Spring Boot)

```bash
cd backend
mvn install
```

Update the `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=root
spring.datasource.password=your_password
```

Start the server:

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

Run unit tests using Mockito:

```bash
mvn test
```

---

## 📬 Contact

📧 **Email:** [raahulmaurya2@gmail.com](mailto:raahulmaurya2@gmail.com)

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more information.

---

⭐ *Fork this repo, report issues, and contribute to make it even better!*
