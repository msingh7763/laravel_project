Laravel Logo

💉 VacciCare — Online Vaccine Management System (OVMS)
A premium, secure, and state-of-the-art immunization scheduling & logistics command center.

Laravel TailwindCSS AlpineJS Vite SQLite

🌟 Introduction
VacciCare is a next-generation web application designed to simplify, automate, and secure the complete vaccination lifecycle. By bridging the gap between national health registries and local distribution clinics, VacciCare provides citizens with a frictionless path to immunization while giving clinic managers high-fidelity inventory and booking controls.

The interface is customized with a premium dark glassmorphism theme, utilizing smooth AlpineJS micro-animations, background particle effects, and dynamic gradients.

✨ Features
👤 Citizen Workspace (Patient Portal)
🛡️ Aadhaar e-KYC Identity Verification: Strict, simulated OTP validation gate connecting to official UIDAI registries. Assures correct identity matching (case/space-insensitive) and masks contact numbers (e.g., XXXXXX1234) for optimal privacy.
📅 Smart Slot Booking: Seamless slot scheduler filtering active medical clinics by city. Supports multiple doses and tracks strict interval resting timelines between doses.
📁 My Appointments: Track the status of active, confirmed, completed, or cancelled vaccination slots.
🌗 Instant Theme Synchronizer: Native light/dark theme toggle stored locally to prevent light flashes during rendering.
👑 Command Control Center (Admin Portal)
📊 Visual Stat Dashboards: Track user counts, active vaccine volumes, clinic clinics, and status-based appointments.
🔥 Most Booked Vaccines: Visual listing identifying high-demand brands for forward supply planning.
📦 Inventory Stock Control: Slot reservations and cancellations automatically decrement and increment live vaccine stocks across clinics.
🏥 Clinic CRUD & Vaccine Registry: Complete hospital clinic allocation controls and vaccine parameter manager (supporting image uploads).
🛠️ Logistics & Communications
✉️ Laravel Mailer: Triggers beautifully-designed, high-fidelity responsive HTML emails with complete slot allocation parameters on successful registration.
🔌 REST APIs: Seamless endpoints (/api/vaccines and /api/appointments) to feed data charts and third-party dashboards.
📦 Tech Stack & Architecture
Backend Framework: Laravel 13.x (PHP 8.3+)
Database Engine: SQLite (stored locally in database/database.sqlite)
Frontend Engine: Blade View Engine + AlpineJS 3.x
Styling System: TailwindCSS v4.0 (integrated natively via Vite)
Asset Bundler: Vite 8.x
Mail Driver: Laravel SMTP Mailer
🚀 Installation & Local Setup
📋 Prerequisites
PHP 8.3 or higher with extensions (sqlite3, curl, mbstring, openssl).
Composer (PHP Dependency Manager).
Node.js (v18+) & NPM.
🛠️ Setup Steps
Clone the Repository:

git clone https://github.com/AmritRaj7461/Online-Vaccine-Management-System.git
cd Online-Vaccine-Management-System
Automated Setup Execution: Run the custom single-command deployment pipeline:

composer run setup
This script auto-creates .env, installs composer dependencies, generates the application key, creates the SQLite file, runs all database migrations + seeds, installs npm assets, and builds resources.

Start Development Server: Run the concurrent hot-reload command:

composer run dev
This starts the PHP artisan server (http://127.0.0.1:8000), background queue listeners, Laravel Pail log tracking, and Vite asset compiler.

🔑 Demo Access Accounts
Once database seeding completes, use these pre-loaded accounts:

Control Panel Admin:
Email: admin@vaccicare.com
Password: password
Patient Citizen (Amrit Mishra):
Email: user@vaccicare.com
Password: password
Aadhaar ID: 123456789012 (Simulated OTP Registry Mobile: XXXXXX0001)
