

https://github.com/user-attachments/assets/66232cbe-510c-404e-8172-29663f054d00



# Cloud Security Governance Platform

A production-quality, visually stunning Cloud Security Governance web application. This platform provides multi-cloud security posture management with a fully animated, glassmorphic dark mode UI.

## Features


- **Multi-Cloud Support**: Top-level switcher to filter data across All Clouds, AWS, Azure, and GCP.
- **Dashboard**: High-level KPIs, 30-day risk trend, findings severity distribution, and compliance posture.
- **Findings & Alerts**: Filterable findings table with a slide-out drawer detailing business impact, remediation steps, and linked compliance controls.
- **Compliance Center**: Framework-specific dashboards (NIST CSF, CIS AWS, ISO 27001, etc.) with radial progress rings and radar charts.
- **Policy Manager**: Manage governance policies and an Exception Management workflow.
- **Asset Inventory**: View all monitored assets with risk scores and tag compliance indicators.
- **Reports**: Generate and download various executive and technical security reports.
- **Settings**: Manage connected accounts, API keys, and notification rules.


## Tech Stack

- **Frontend**: Vite + React (TypeScript)
- **Styling**: Tailwind CSS (custom glassmorphism design system)
- **Visuals**: Framer Motion (page transitions, micro-interactions) & Recharts (animated charts)
- **Icons**: Lucide React
- **Backend**: Node.js + Express (mock REST API server)

## Setup Instructions

### Prerequisites
Make sure you have Node.js and npm installed.

### 1. Start the Backend API
The backend is a lightweight Express server that serves hardcoded mock JSON data.
From the root of the project, run:
```bash
node server/index.js
```
The mock API will start on `http://localhost:3001`.

### 2. Start the Frontend Application
Open a new terminal window in the root directory.
Install the dependencies and start the Vite development server:
```bash
npm install
npm run dev
```
The frontend will be available at `http://localhost:5173`. 
The Vite server is configured to proxy or connect to the backend API seamlessly.

## Usage
- Open `http://localhost:5173` in your browser.
- The **Login** screen accepts *any* credentials (demo mode).
- Explore the dashboard, switch between cloud providers in the top bar, and navigate through the side menu to view different modules of the platform.
