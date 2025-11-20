OEE Masterclass: Smart Factory Simulation 🏭

An interactive, "Digital Twin" educational experience designed to teach Overall Equipment Effectiveness (OEE) to students and early professionals

📖 Overview

OEE Masterclass is a single-page web application that simulates a high-speed bottling line. It gamifies the learning of OEE concepts by allowing users to act as a Plant Manager for a shift.

Instead of reading dry definitions, users interact with a live production line, understanding real-world issues like Equipment Failure, Micro-stops, and process defects to see how they impact efficiency and the bottom line.

🚀 Features

** interactive Simulation Modules**: Three distinct phases to master the OEE formula:

Availability (A): Manage breakdowns and setup times.

Performance (P): Balance run speed against micro-stops (jams).

Quality (Q): Visualize yield losses like startup rejects.

Real-Time Visualization: A reactive "Digital Twin" animation that visually responds to your inputs (e.g., belt jams, red warning lights, scrap rejection).

Financial Impact Monitor: A dynamic calculator that translates OEE % losses directly into Opportunity Cost ($) based on user-defined unit costs.

Benchmarking Suite: Compare your shift performance against "World Class" (85%) and "Industry Average" (60%) standards.

Smart Audio Engine: Browser-native industrial soundscapes providing auditory feedback for machine states and alarms.

Session Persistence: Your simulation progress is automatically saved, allowing you to resume your shift later.

🧠 Educational Value

This tool breaks down the "Six Big Losses" of manufacturing:

Availability Loss: Unplanned Stops (Breakdowns) & Planned Stops (Changeovers).

Performance Loss: Small Stops (Idling) & Reduced Speed (Slow Cycles).

Quality Loss: Production Rejects & Startup Rejects.

Users learn that OEE is not just a number, but a multiplier:

90% Availability × 90% Performance × 90% Quality = 72.9% OEE (Not 90%!)

🛠️ Technology Stack

Frontend: React 18 (via CDN for portability)

Styling: Tailwind CSS (Utility-first design)

Icons: Phosphor Icons

Audio: Web Audio API (Native browser synthesis)

Architecture: Single File Component (SFC) - No build step required!

📦 How to Run

Option 1: Live Web Version

https://cobra-coder.github.io/OEE-masterclass/

Option 2: Run Locally

Download the index.html file from this repository.

Open the file directly in any modern web browser (Chrome, Edge, Safari).

Note: For the best experience, run it on a full-screen desktop or tablet kiosk.

👨‍🏫 Usage Guide

Start Shift: Begin the simulation from the "Mission Briefing" screen.

Diagnose: Move through the modules (Availability -> Performance -> Quality).

Adjust: Use the sliders to simulate real-world scenarios (e.g., increase breakdown time to see OEE drop).

Analyze: In the final Report phase, review the Loss Analysis panel to see specific recommendations (e.g., SMED, Six Sigma) for your biggest losses.

Calculate Cost: Input your specific Cost per Minute and Cost per Unit to see the financial impact of your efficiency losses.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

© Designed by Madhusudan Chhangani
