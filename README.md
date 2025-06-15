# 🎯 Questa Quiz App

An advanced, full-stack **AI-powered Quiz Platform** built with the **MERN Stack** — take quizzes, auto-generate questions using AI, track performance, and battle friends in real-time!

---

## 🌐 Live Demo  
🚀 [Try It Now]()

---

## ✨ Key Features

- 🔐 **Authentication & Roles**
  - Google OAuth + JWT
  - Roles: User, Premium, Admin

- 🤖 **AI Quiz Generation**
  - Auto-create questions with duration & marks
  - Evaluate written answers with NLP

- 📊 **Reports & Insights**
  - Quiz history, score breakdowns, and reviews

- 🏆 **Leaderboards & Achievements**
  - See top scorers (weekly/monthly)
  - Earn badges like “Quiz Master” & “Speed Genius”

- ⚔️ **Live Quiz Battles** *(Coming Soon!)*
  - Real-time challenge mode with friends

- 💳 **Subscription Plans**
  - 🆓 Free: Limited quizzes
  - 💎 Premium: Unlimited access + AI Insights

- 🛡️ **Admin Panel**
  - Manage users, quizzes, and platform analytics

---

## 🛠️ Tech Stack

- **Frontend**: React + Vite + Tailwind CSS
- **Backend**: Node.js + Express.js + MongoDB
- **AI**: Together AI, Google Gemini API
- **Auth**: Google OAuth, JWT
- **Deployment**: Render

---

## 📦 Installation & Setup

### 🔧 Backend Setup

```bash
cd backend
npm install
````

Create `.env` in the `backend` folder:

```env
MONGO_URI=your_mongodb_uri
PORT=4000
TOGETHER_AI_API_KEY=your_ai_key
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GOOGLE_CALLBACK_URL=http://localhost:4000/auth/google/callback
FRONTEND_URL=http://localhost:5173
GEMINI_API_KEY=your_gemini_api_key
```

Start backend:

```bash
npm start
```

---

### 💻 Frontend Setup

```bash
cd frontend
npm install
```

Create `.env` in the `frontend` folder:

```env
VITE_BACKEND_URL=https://your-backend-url.onrender.com
VITE_CONTACT_KEY=your_emailjs_key
VITE_CONTACT_SERVICE=your_emailjs_service
VITE_CONTACT_TEMPLATE=your_emailjs_template
```

or for local:

```env
VITE_BACKEND_URL=http://localhost:4000
```

Start frontend:

```bash
npm run dev
```

---

## ✅ Completed Features

* 🧠 AI question generation
* ⏳ Timed quizzes
* 🔐 Auth with roles (User, Premium, Admin)
* ✍️ AI-evaluated written tests
* 📊 Performance reports & reviews
* 📈 Leaderboards
* 🏅 Achievement Badges:

  * Quiz Master
  * Speed Genius
  * Perfect Score
* 💎 Premium Access: More features + insights

---

## 🔄 In Progress

* ⚔️ **Live Quiz Battles**

  * Real-time player vs player quiz mode
  * Live leaderboard and timer tracking

---

## 👨‍💻 Author

Made with ❤️ by [**AbhisekhNayek**](https://github.com/AbhisekhNayek)
© 2025 All rights reserved.

> 📩 Feel free to reach out for collaborations, feedback, or ideas!


---

## 🙌 Feedback & Contributions

Have suggestions or want to contribute?
Open an issue or pull request — **PRs are welcome!**

---

## 📎 License

MIT License — Use freely with attribution.


