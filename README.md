# CyberShield APK Analyzer

CyberShield APK Analyzer is a web-based prototype designed to simulate the detection of fake and malicious banking applications. Built by the **"No_Code" Team from SRIT**, this tool provides an intuitive visual representation of how an AI-powered APK analysis system evaluates Android application packages (.apk files) for security threats.

## ✨ Features

- **File Upload Interface:** Drag-and-drop or click to upload `.apk` files for scanning.
- **Simulated Analysis Engine:** Demonstrates a comprehensive 4-step security checking process:
  1. Analyzing digital signature and package metadata.
  2. Performing static code analysis.
  3. Detecting patterns with AI/ML models.
  4. Finalizing risk score and generating reports.
- **Dynamic Risk Scoring:** Dynamically calculates risk scores based on file names, mimicking the detection of common malicious keywords (e.g., "mod", "hack", "bank").
- **Security Report Generation:** Displays file details (size, mock hash), a visual risk meter, suspicious permissions found, and actionable security recommendations based on the detected threat level (Low, Medium, High Risk).

## 🛠️ Technologies Used

- **HTML5 & CSS3**: Core structure and custom styling.
- **JavaScript (Vanilla)**: DOM manipulation and simulated logic.
- **Tailwind CSS**: Rapid UI development via CDN.
- **Feather Icons**: Modern, lightweight SVG icons.

## 🚀 Getting Started

### Prerequisites

All you need is a modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.). No backend server or database setup is required.

### Installation & Usage

1. Clone or download the repository to your local machine.
2. Navigate to the project folder.
3. Open the `index.html` file in your default web browser.
4. Click on the upload area to select a sample `.apk` file from your device, or simply drag and drop a file.
5. Click **Scan File** to trigger the analysis simulation and view the generated security report.

## ⚠️ Disclaimer

**This is a front-end prototype and simulation.** It does not perform actual static or dynamic binary analysis on the uploaded APK files. All analysis steps, risk scores, extracted permissions, and hashes are mocked using JavaScript logic purely for demonstration and UI/UX conceptualization purposes. No files are uploaded to any server.

## 👥 Team

Developed by the **"No_Code" Team from SRIT**.
