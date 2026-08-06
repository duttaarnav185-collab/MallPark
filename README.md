MallPark Pro — Smart AI-Powered Mall Parking System
MallPark Pro is an interactive, real-time web-based parking management dashboard designed for shopping centers and multi-level facilities. Built using modern web technologies, it features dynamic light/dark mode support, real-time AI route guidance, live vehicle activity simulation, dynamic peak-rate pricing, and simulated automated barrier gates.

🚀 Features
Dynamic Light & Dark Mode: Adapts the entire UI, including realistic asphalt driveways, parking slot cards, and control panels, to both light and dark themes.

Interactive Floor Layout Toggle: The Available Slots metric card acts as a toggle button to reveal or collapse the interactive live parking floor map.

AI Navigation & Route Guidance: Visualized paths guide drivers from the entry gate directly to their designated parking slot.

Multi-Floor Management: Seamlessly switch between Floor 1 (Ground Level), Floor 2 (Executive Level), and Floor 3 (Roof Level).

ANPR & Vehicle Search: Quick lookup via license plate numbers with built-in Indian standard plate format validation (MH12AB1234).

Automated Ticket & Receipt Generation: Generates dynamic digital QR code passes upon booking and itemized thermal receipts upon checkout.

Real-time Activity Feed & Live Simulation: Background simulation of vehicles entering, exiting, and charging at EV stations, complete with an audit log.

Emergency Corridor & Peak Hours Surcharge: Support for emergency clearance mode and dynamic 1.5x peak pricing surcharges.

Audio Feedback Engine: Web Audio API sound synthesizer providing interactive audio cues for clicks, success events, alarms, and gate movements.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling & Design: Tailwind CSS (CDN with dynamic class dark mode), FontAwesome 6 Icons

Data Visualization: Chart.js (Doughnut Chart for slot distribution)

API Utilities: QR Code Generator API for pass generation

Audio: Native Web Audio API (Synthesizer)

📁 Project Structure
Plaintext
mallpark-pro/
├── index.html        # Monolithic single-page application (HTML, CSS, JavaScript)
└── README.md         # Project documentation
🚦 Getting Started
Prerequisites
No complex installation or build steps are required. All external libraries (Tailwind CSS, FontAwesome, Chart.js) are loaded via lightweight CDNs.

Running the Application
Clone or Download the repository:

Bash
git clone https://github.com/your-username/mallpark-pro.git
cd mallpark-pro
Open index.html in any web browser:

Double-click index.html in your file explorer, OR

Use a local dev server extension like VS Code Live Server.

📖 How to Use
View Live Layout: Click on the Available Slots card at the top to toggle the live smart parking layout display.

Book a Slot: Click on any empty slot card (e.g., F1-S01) to open the reservation modal, fill in driver details, and generate a QR ticket pass.

Find & Route Vehicle: Type a vehicle plate number into the search bar and click Find & Route. The system will switch to the appropriate floor and draw an animated AI guidance path.

Checkout: Enter a plate number into the search bar and click Checkout to process exit gate opening and print an official thermal receipt.

Toggle Theme: Click the moon/sun icon in the top navigation bar to toggle between Light and Dark modes.
