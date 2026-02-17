# 🏥 FITTRACKAI - Web Application

**Web application for FitTrackAI capstone project. Features calorie tracking, health assessment dashboard, Filipino meal planner, and AI chatbot for dietary guidance.**

> Capstone Project: "FITTRACKAI: A Machine Learning-Based System for Personalized Health Assessment and Calorie Tracking with Dietary Guidance"

---

## 🌟 Features

### 📊 FitTrackAI Dashboard
- Real-time health metrics (BMI, BMR, TDEE, BSA, WHR, WtHR)
- Body measurements tracking (Height, Weight, Waist, Hip)
- Nutrition summary (Protein, Carbs, Fat, Food entries)
- Personalized calorie goals based on TDEE
- Daily progress visualization

### 🍱 Filipino Meal Planner
- Automated meal plan generation
- 290+ Filipino food database
- Smart meal combinations (Breakfast, Lunch, Dinner, Snacks)
- Macro-nutrient breakdown
- Accurate calorie matching (within 10% of target)

### 📝 Food Diary & Calorie Tracking
- Daily food logging with meal categorization
- Smart food search with 8 categories
- Edit and delete entries
- Real-time remaining calorie calculator
- Device sync support (mobile/wearable integration)

### 📈 Weight Tracking
- Visual weight progress charts
- Weight history log
- Track changes over time

### 💬 AI Chatbot Assistant
- Personalized dietary recommendations
- Custom meal plan generation
- Filipino food guidance

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
