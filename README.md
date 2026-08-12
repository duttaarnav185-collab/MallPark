<div align="center">

# 🚗 MallPark Pro – Smart AI-Powered Mall Parking System

### Intelligent • Automated • Real-Time Parking Management

*An enterprise-grade, AI-powered parking management dashboard designed for shopping malls, commercial complexes, and multi-level parking facilities.*

</div>

---

## 📌 Overview

**MallPark Pro** is an interactive, real-time parking management system built entirely on modern web technologies. The platform bridges the gap between administrators and mall visitors by combining artificial intelligence, live vehicle monitoring, automated ticketing, smart navigation, and dynamic pricing to create a seamless parking experience.

The project focuses on maximizing:
*   **Vehicle flow efficiency** through AI-guided routing.
*   **Parking slot utilization** with real-time tracking.
*   **Driver convenience** via instant check-ins and advance reservations.
*   **Facility security** through strict visitor guidelines and CCTV monitoring features.
*   **Revenue optimization** via dynamic peak-hour pricing and overstay penalties.

---

## ✨ Core Features

### 👤 Dual-Portal System
*   **Manager Portal (Admin Suite):** Access live slot distribution, activity logs, revenue metrics, emergency controls, and manual slot overrides.
*   **Visitor Portal:** Instant check-in, premium advance slot reservation, and direct AI-navigation to vehicles.

### 🗺️ Interactive Smart Floor Layout
*   **Multi-Floor Management:** Seamlessly switch between Floor 1 (Ground), Floor 2 (Executive), and Floor 3 (Roof).
*   **Real-time Visualization:** Expandable parking map with color-coded interactive slot selection (Green for Available, Grey for Occupied, Orange/Yellow for Reserved).
*   **Traffic Monitoring:** Live tracking of daily and total website/facility visits.

### 🎫 Advanced Booking & Digital Ticketing
*   **Flexible Modes:** Choose between standard **Instant Check-in** or premium **Reserve Advance** (with a 2.5x surcharge).
*   **Digital Passes:** Auto-generates QR code-based entry passes and detailed thermal checkout receipts.
*   **Smart Pricing:** Automated duration-based fee calculation integrated with dynamic peak-hour multipliers.

### 🤖 AI Route Guidance & ANPR Search
*   **Smart Navigation:** Intelligent path generation drawing a direct route from the entry gate to the assigned slot.
*   **Vehicle Search:** Indian number plate recognition support (e.g., `MH12AB1234`) for fast vehicle lookup and routing.

### 🚨 Security & Dynamic Controls
*   **Visitor Guidelines:** Highlighted, moving digital banners instructing users on parking etiquette and strict 24/7 CCTV surveillance tracking.
*   **Emergency Mode:** One-click emergency clearance that restricts ground-floor access and opens all barrier gates.

### 📈 Live Activity Simulation & Audio
*   **Simulated Traffic:** Automated vehicle entries, exits, and EV charging status tracking.
*   **Audio Feedback:** Web Audio API integration for button clicks, gate movements, success chimes, and warning alerts.

---

## 🛠️ Technology Stack

| Category | Technologies |
| :--- | :--- |
| **Frontend Core** | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| **Styling** | Tailwind CSS |
| **Icons & Fonts** | Font Awesome 6, Google Fonts (Inter, JetBrains Mono) |
| **Data Visualization** | Chart.js (Real-time Occupancy Doughnut Charts) |
| **External APIs** | QR Code Generator API |
| **Native APIs** | Web Audio API (Sound), LocalStorage (Traffic Monitoring) |

---

## 📂 Project Structure

```plaintext
mallpark-pro/
│
├── index.html          # Main application (All logic, styles, and markup)
└── README.md           # Project documentation

