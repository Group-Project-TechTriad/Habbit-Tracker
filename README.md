# 🌟 Habit Tracker / Productivity App

A simple yet powerful **habit tracking web app** that helps users build consistency, track progress with streaks, and stay motivated through **gamification (XP, levels, achievements)**.  

![Build](https://img.shields.io/badge/build-passing-brightgreen)  
![License](https://img.shields.io/badge/license-MIT-blue)  
![Status](https://img.shields.io/badge/status-in%20progress-yellow)  

---

## ✨ Features
- [ ] User Authentication (Sign up, Login, Google OAuth)
- [ ] Create, edit, delete habits
- [ ] Calendar view for daily/weekly habit tracking
- [ ] Streak tracking with 🔥 streak counter
- [ ] Gamification with XP, badges, and levels
- [ ] Reminders & notifications
- [ ] Analytics & progress reports

---

## 🖼️ Demo
> Add screenshots or GIFs here once the app is running.  

Example placeholders:  

![Dashboard Screenshot](docs/dashboard.png)  
![Calendar Screenshot](docs/calendar.png)  

---

## 🛠️ Tech Stack
**Frontend:**
- React + TailwindCSS
- Axios for API calls  

**Backend:**
- Node.js + Express  
- JWT Authentication  

**Database:**
- MySQL (Sequelize ORM)  

**Deployment:**
- Frontend: Vercel / Netlify  
- Backend: Render / Railway  
- Database: PlanetScale / Supabase  

---

## 📂 Project Structure







---

## ⚙️ Installation & Setup

### 🔑 Prerequisites
- Node.js v18+  
- MySQL (or any SQL DB)  
- Git  

### 🚀 Steps
```bash
# 1. Clone repo
git clone https://github.com/username/habit-tracker.git
cd habit-tracker

# 2. Backend setup
cd backend
npm install
cp .env.example .env   # Update DB credentials
npm run dev

# 3. Frontend setup
cd ../frontend
npm install
npm start

