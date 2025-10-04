# 🚀 RouteAhead: Predictive Commuter & Travel Manager

## Project Goal & Overview 💡

**RouteAhead** is a powerful, client-side web application designed to solve one of the biggest daily stressors: **the uncertainty of travel time.**

Instead of relying on static schedules, this tool provides **actionable intelligence** by calculating the exact moment you need to leave the house to arrive at your destination on time. It achieves this by accounting for real-world factors like **simulated traffic** and **transit delays**.

This demonstrates mastery of client-side logic, data persistence, and building an urgent, professional user interface (UI/UX).


## Technical Achievements (The Core Value)

### 1. Predictive Time Logic

* **Advanced Calculation:** Uses precise JavaScript time logic to determine the optimal **"Leave Home By"** time, incorporating your scheduled departure, safety buffer, and dynamically generated delay/traffic factors.
* **Real-Time Status Alerts:** The main status card changes **color (Red/Green)** and applies an **urgent pulse animation** (via custom CSS Keyframes) to signal critical delays or early departures.

### 2. Data Persistence & Management

* **Location Management:** Users can save multiple named **Origins** and **Destinations** (addresses or GPS coordinates), eliminating repetitive typing.
* **Future Trip Manager:** Allows travelers to save complex trip details for days or months in advance, providing **predictive rush-hour alerts** for those scheduled travel times.
* **Local Storage:** All user data (settings, locations, and future trips) is securely saved using **Local Storage**, ensuring a seamless, consistent experience across browser sessions.

### 3. Integration & UI/UX

* **Geolocation & Mapping:** Retrieves the user's **live GPS coordinates** upon request and dynamically generates a precise, traffic-aware **Google Maps link** using the stored Origin and Destination values.
* **Professional Design:** Features a responsive, card-based interface built with **Tailwind CSS** utilities, focusing on clarity, immediate feedback, and professional aesthetics.


## ⚙️ Technologies Used

* **HTML5 & CSS3 (Tailwind):** Structured UI with responsive design principles.
* **Vanilla JavaScript (ES6+):** All core logic, time calculation, data handling, and DOM rendering.
* **Browser APIs:** `navigator.geolocation` (Live GPS), `Date` object (Time management).


\[🚀 **View Live Demo** - *Link to your deployed website here!*]
