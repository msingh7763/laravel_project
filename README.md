# 💉 VacciCare — Online Vaccine Management System (OVMS)

> A premium, secure, and state-of-the-art immunization scheduling & logistics command center.

![Laravel](https://img.shields.io/badge/Laravel-13.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v4.0-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)
![AlpineJS](https://img.shields.io/badge/AlpineJS-v3-77C1D2?style=for-the-badge&logo=alpinedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

---

# 🌟 Introduction

**VacciCare** is a next-generation web application designed to simplify, automate, and secure the complete vaccination lifecycle.

By bridging the gap between national health registries and local distribution clinics, VacciCare provides citizens with a frictionless path to immunization while giving clinic managers high-fidelity inventory and booking controls.

The interface is customized with a premium dark glassmorphism theme, utilizing smooth AlpineJS micro-animations, background particle effects, and dynamic gradients.

---

# ✨ Features

## 👤 Citizen Workspace (Patient Portal)

### 🛡️ Aadhaar e-KYC Identity Verification
- Simulated OTP validation system
- UIDAI-style registry verification
- Case-insensitive & space-insensitive matching
- Mobile number masking for privacy  
  Example: `XXXXXX1234`

### 📅 Smart Slot Booking
- Search active vaccination clinics by city
- Multi-dose vaccine support
- Dose interval validation system
- Real-time appointment scheduling

### 📁 My Appointments
Users can:
- Track appointment status
- View confirmed slots
- Monitor completed/cancelled appointments

### 🌗 Instant Theme Synchronizer
- Light/Dark mode toggle
- Local theme persistence
- Prevents UI flashing during rendering

---

# 👑 Command Control Center (Admin Portal)

## 📊 Visual Dashboard Analytics
- Total users count
- Active vaccine inventory
- Clinic management statistics
- Appointment analytics

## 🔥 Most Booked Vaccines
- Identify high-demand vaccine brands
- Helps optimize logistics planning

## 📦 Inventory Stock Control
- Automatic stock decrement on booking
- Automatic stock restoration on cancellation
- Real-time inventory updates

## 🏥 Clinic CRUD & Vaccine Registry
- Full clinic management system
- Vaccine parameter management
- Vaccine image upload support

---

# 🛠️ Logistics & Communications

## ✉️ Laravel Mailer Integration
Beautiful responsive HTML emails are automatically sent after successful booking with:
- Appointment details
- Vaccine information
- Clinic allocation details

## 🔌 REST APIs

Available API endpoints:

```bash
/api/vaccines
/api/appointments
