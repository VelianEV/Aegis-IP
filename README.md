# Aegis-IP

# Aegis-IP

Here is a README file documenting the **initial** version of the Aegis IP system (the original `.html` file you provided), highlighting its original features and known limitations prior to the revisions.

---

# AEGIS IP — Autonomous Counterfeit Radar (Initial Prototype)

## 📌 Overview

**AEGIS IP** is an AI-powered cybersecurity dashboard designed to detect and track counterfeit products across global e-commerce platforms. Built for the Web Data UNLOCKED Hackathon, this tool leverages web scraping and artificial intelligence to identify intellectual property infringements, price anomalies, and suspicious seller networks.

This repository/file contains the **initial frontend prototype** packaged as a standalone HTML file.

## 🚀 Features (V1)

* **Threat Dashboard:** A centralized interface displaying active threats, items removed, financial impact, and average AI confidence.
* **Counterfeit Detection List:** A tabular view of detected counterfeit goods, listing the target brand, platform/seller, pricing anomalies, and the AI's counterfeit probability.
* **Threat Geography:** A basic global map interface intended to visualize the origin of active high-risk counterfeiting networks.
* **Bright Data Integration:** UI elements indicating integration with Bright Data's Web Unlocker and SERP API for scraping e-commerce DOM structures.
* **Export Options:** Buttons included for generating CSV data reports and PDF intelligence reports.

## 🛠️ Technology Stack

* **Frontend Framework:** React (Bundled/minified)
* **Styling:** Tailwind CSS
* **Icons:** Lucide-React / SVG Icons
* **Format:** Single-file monolithic HTML execution

## 💻 How to Run (Standalone HTML)

Because this initial prototype was compiled into a single HTML file, no complex server setup is required to view the UI.

1. Download the `aegis-ip.html` file to your local machine.
2. Double-click the file to open it in your default modern web browser (Google Chrome, Firefox, Safari, or Edge).
3. Alternatively, open it in VS Code and use the **Live Server** extension to view the dashboard.

## ⚠️ Known Issues & Limitations (To-Do List)

As this is an early hackathon prototype, several features in this specific version are incomplete or buggy:

* **Broken External Links:** The URLs/links to the actual counterfeit products on external e-commerce sites are currently unclickable or fail to route properly.
* **Export Bugs:** The "Export CSV" and "Export PDF" functionalities are currently non-operational or produce broken files.
* **Map Accuracy:** The threat map is generic and lacks accurate, comprehensive geographical plotting for the detected seller locations.
* **Basic AI Output:** The AI verdict currently only provides a binary/simple confidence score without deep forensic explanations (e.g., computer vision breakdowns or NLP sentiment analysis).
* **Simulated Scraping:** The Bright Data integration requires strengthening to move beyond UI representation into a functional terminal/live scraping pipeline.

## 🤝 Hackathon Context

This project was conceived for the **Web Data UNLOCKED Hackathon** (May 2026). It aims to demonstrate how unlocking live web data can fuel AI agents to protect brand equity and combat global counterfeit supply chains.
