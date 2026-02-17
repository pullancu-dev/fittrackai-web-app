# 🏥 FITTRACKAI - Web Application

**Web application for FitTrackAI capstone project. Features calorie tracking, health assessment dashboard, Filipino meal planner, and AI chatbot for dietary guidance.**

> Capstone Project: "FITTRACKAI: A Machine Learning-Based System for Personalized Health Assessment and Calorie Tracking with Dietary Guidance"

---

## 🌟 Features
- 📊 **Dashboard** — Health metrics (BMI, BMR, TDEE, BSA, WHR, WtHR), body measurements, nutrition summary
- 🍱 **Filipino Meal Planner** — Auto-generated plans from 290+ food database, macro breakdown, ≤10% calorie accuracy
- 📝 **Food Diary** — Daily logging, food search, edit/delete entries, device sync
- 📈 **Weight Tracking** — Visual progress chart, weight history log
- 💬 **AI Chatbot** — Personalized dietary recommendations, custom meal plans

## 🎯 Live Demo

**Try the app:** [https://pullancu-dev.github.io/fittrackai-web-app]

## 🛠️ Technologies

### Core
- **HTML5, CSS3, JavaScript** (Vanilla JS)
- **PapaParse** (CSV processing)
- **Chart.js** (Weight progress visualization)

### Backend & Database
- **Firebase Firestore** (Dual-instance architecture)
  - Primary: User profiles & body measurements
  - Secondary: Nutrition logs & food diary
- Real-time data synchronization

### AI Integration
- **Anthropic Claude API** (AI Chatbot via iframe)
- **Custom Filipino Food Database** (290+ dishes)

### Features
- Responsive mobile-first design
- SVG-based progress rings
- Real-time calorie tracking
