# 🌤️ Mood Tracker App

A simple yet powerful **Mood Tracking Web Application** built using **Node.js, Express.js, EJS, and MongoDB**.  
This app allows users to record their daily moods, view emotional trends through charts, and reflect on their mental well-being over time.

---

## 🧠 Overview

We often go through days without realizing how our mood changes or what affects it.  
The **Mood Tracker App** helps users:
-🔐 User Authentication (Login/Signup)
- Log daily moods and notes,
- Track emotional patterns,
- Visualize trends with interactive charts,
- And reflect for personal growth.
- ☁️ Export mood history as PDF/CSV
It’s simple, fast, and visually clean — perfect for anyone who wants to stay mindful.

---

## ✨ Features

✅ Add, edit, and delete mood entries  
✅ View your daily and weekly mood history  
✅ Interactive charts to visualize mood trends  
✅ Responsive EJS-based UI  
✅ MongoDB integration for data storage  
✅ Deployable easily via Render or GitHub  

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML, CSS, EJS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Atlas) |
| **Charting** | Chart.js |
| **Version Control** | Git & GitHub |
| **Deployment** | Render / Vercel / Railway |

---

## 📂 Folder Structure



MoodTracker/
│
├── models/ # Mongoose schemas for storing moods
├── views/ # EJS templates (frontend pages)
├── public/ # CSS, JS, and static files
├── server.js # Main Express server
├── .env # Environment variables
└── package.json # Dependencies and project info


---

## ⚙️ Installation & Setup

Follow these steps to run the app locally 👇

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/mood-tracker.git
cd mood-tracker

2️⃣ Install Dependencies
npm install

3️⃣ Create a .env File

In the project root, create a .env file and add:

PORT=3000
MONGO_URI=your_mongodb_atlas_connection_string

4️⃣ Start the Server
npm start

5️⃣ Open in Browser

Visit 👉 http://localhost:3000

🌍 Deployment

You can deploy this app for free using:

Backend: Render
, Vercel
, or Railway

Database: MongoDB Atlas

Version Control: GitHub

Once deployed, set your MONGO_URI and PORT as environment variables in your hosting platform.

🧭 How It Works

The user opens the app and selects their current mood (e.g., Happy, Sad, Neutral).

Optionally adds a short note for context.

The entry is saved in MongoDB.

The dashboard shows mood data with date filters and charts.

🚀 Future Improvements



📱 Make it a PWA (installable web app)

🤖 AI-powered Mood Predictions

🗓️ Calendar-based Mood Insights

