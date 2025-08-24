# 🏥 PulseBridge HMS

A modern **Hospital Management System** built with **Next.js 14 (App Router)**,  
featuring dark mode, smooth transitions, and a modular dashboard for Patients, Appointments, and Billing.  

---

## ✨ Features
- 🌙 **Dark/Light mode toggle** (global context, persists across pages)  
- 🎭 **Page transition animations** with Framer Motion  
- 📋 **Patients module** – simple table view for records  
- 📅 **Appointments module** – appointment list with doctor assignments  
- 💳 **Billing module** – patient bills with status display  
- 🧭 **Dashboard layout** with navigation links  

---

## 📂 Project Structure
pulsebridge-hms/
├── app/
│ ├── layout.js # Main layout (with Navbar + DarkMode toggle)
│ ├── page.js # Dashboard landing page
│ ├── patients/page.js # Patients module
│ ├── appointments/page.js # Appointments module
│ ├── billing/page.js # Billing module
│
├── components/
│ ├── Navbar.js # Top navigation bar
│ ├── DarkModeToggle.js # Theme toggle button
│ ├── TransitionWrapper.js # Page transition wrapper (Framer Motion)
│ └── ThemeContext.js # Context provider for dark mode
│
├── styles/
│ └── globals.css # Tailwind base + custom styles
│
├── tailwind.config.js
├── package.json
└── README.md
