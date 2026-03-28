# 📊 BUDI MADANI AI Forecaster (Native Web App)

A high-performance, bilingual Single Page Application (SPA) designed to help Malaysian citizens navigate the 2026 targeted subsidy framework. This tool provides real-time financial forecasting for RON95 fuel quotas and features an integrated AI advisor for policy guidance.

## 🚀 Live Demo
**Check out the live application here:** [[INSERT YOUR NETLIFY LINK HERE]](https://69c811d87ba84a929e4058ab--budi-forecaster.netlify.app/)

---

## ✨ Key Features

### ⛽ Predictive Fuel Engine
* **Real-Time Calculations:** Instantly forecasts monthly fuel expenditure and "Days Until Cliff" (quota exhaustion) based on user driving habits.
* **Dynamic Visualization:** Integrated **Chart.js** to provide an animated 30-day burn rate projection against the government's 200L subsidy limit.
* **Market Penalty Alerts:** Automated UI state changes that highlight financial exposure when users exceed their allocated quota.

### 🤖 Gemini AI Advisor
* **REST API Integration:** Connected to **Google Gemini** to provide a context-aware financial assistant.
* **Policy Guidance:** Trained to answer complex queries regarding PADU, STR/SARA eligibility, and 2026 fuel regulations.

### 🌍 Global Accessibility (i18n)
* **Instant Translation:** A custom-built JavaScript i18n engine allowing seamless UI switching between **English, Bahasa Melayu, Mandarin, and Tamil** with zero page reloads.
* **Localization:** All dynamic math warnings and AI responses are tailored to the selected language.

---

## 🛠️ Technical Stack
* **Frontend:** HTML5, Tailwind CSS (Utility-first styling)
* **Engine:** Vanilla JavaScript (ES6+)
* **Graphics:** Chart.js (Data Visualization)
* **AI:** Google Gemini API (Natural Language Processing)
* **Deployment:** Netlify (CI/CD)

---

## 📂 Project Structure
```text
BUDI-Pro/
├── index.html        # The entire SPA (Structure, Logic, and Styles)
└── README.md         # Project Documentation
