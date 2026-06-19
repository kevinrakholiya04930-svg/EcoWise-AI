# 🌱 EcoWise AI
### Carbon Footprint Awareness Platform

![React](https://img.shields.io/badge/React-18.3.1-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.2.11-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.4-06B6D4?logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-LTS-339933?logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-4.19.2-000000?logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Authentication-000000?logo=jsonwebtokens&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini_AI-Powered-4285F4?logo=google-gemini&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-Deployed-000000?logo=vercel&logoColor=white)

![Status](https://img.shields.io/badge/Status-Completed-success)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![PRs](https://img.shields.io/badge/PRs-Welcome-brightgreen)
![Maintained](https://img.shields.io/badge/Maintained-Yes-success)
![Hackathon](https://img.shields.io/badge/Hackathon-Hack2Skill_Prompt_Wars-orange)

> Empowering individuals to understand, track, and reduce their carbon footprint through personalized insights, AI recommendations, and sustainability-driven actions.

---

# 🏆 Hackathon Challenge

**Hack2Skill Prompt Wars – Challenge 3**

### Problem Statement
Design a solution that helps individuals understand, track, and reduce their carbon footprint through simple actions and personalized insights.

---

# 🎯 Chosen Vertical

**Sustainability & Climate Awareness**

EcoWise AI helps users:

- Understand their environmental impact
- Track emissions from daily activities
- Receive personalized sustainability insights
- Simulate eco-friendly lifestyle changes
- Stay motivated through gamification

---

# 🚀 Project Overview

Climate change is one of the biggest global challenges. However, most individuals do not understand how their everyday activities contribute to carbon emissions.

EcoWise AI bridges this gap by transforming complex sustainability data into simple, actionable insights.

The platform calculates carbon emissions based on user lifestyle patterns and provides intelligent recommendations to help users make environmentally conscious decisions.

---

# ✨ Key Features

## 🔐 Authentication
- JWT Authentication
- Secure Password Hashing
- Protected Routes
- Session Persistence

---

## 👋 Smart Onboarding
Collects user information including:

- City
- Transportation Habits
- Daily Travel Distance
- Electricity Consumption
- Food Preferences
- Digital Device Usage
- Work Style
- Sustainability Goals

### Additional Features
- Multi-step wizard
- Auto-save progress
- Progress restoration
- Prevent data loss
- Validation support

---

## 🌍 Carbon Footprint Engine

Calculates emissions from:

### 🚗 Transportation
- Car
- Bike
- Bus
- Metro
- Walking
- Remote Work

### ⚡ Electricity Usage
Monthly electricity consumption analysis.

### 🍽 Food Habits
Different dietary patterns and their environmental impact.

### 💻 Digital Activities
Daily screen time and digital device usage.

Provides:

- Total Carbon Footprint
- Category-wise Emissions
- Carbon Score
- Equivalent Trees Required
- Environmental Impact Insights

---

## 🤖 AI Sustainability Coach

Provides:

- Personalized recommendations
- Emission explanations
- Sustainability guidance
- Eco challenges
- Future predictions

---

## 🎮 Gamification

Users earn:

- Green Points
- Levels
- Badges
- Achievements
- Sustainability Milestones

---

# 🧠 Approach & Logic

EcoWise AI follows a user-centric approach:

### Step 1
Authenticate user securely.

↓

### Step 2
Collect lifestyle information through onboarding.

↓

### Step 3
Generate personalized carbon profile.

↓

### Step 4
Calculate emissions using Carbon Engine.

↓

### Step 5
Create sustainability persona.

↓

### Step 6
Provide AI-driven recommendations.

↓

### Step 7
Reward users for sustainable actions.

---

# 🔄 Application Flow

```mermaid
flowchart TD

A[User Registration/Login]
--> B[Smart Onboarding]

B --> C[Transportation Data]
B --> D[Electricity Data]
B --> E[Food Preferences]
B --> F[Digital Usage]

C --> G[Carbon Engine]
D --> G
E --> G
F --> G

G --> H[Emission Calculation]
H --> I[Carbon Score]
H --> J[Environmental Equivalents]

I --> K[AI Sustainability Coach]
J --> K

K --> L[Dashboard]
L --> M[Analytics & Insights]
L --> N[Gamification System]

flowchart LR

Frontend[React + Tailwind]
<--> Backend[Node.js + Express]

Backend
<--> Database[(MongoDB)]

Backend
--> CarbonEngine[Carbon Calculation Engine]

Backend
--> AI[Gemini AI Services]

Backend
--> Gamification[Rewards System]