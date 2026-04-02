

<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&pause=1000&color=00C853&center=true&vCenter=true&width=700&lines=GapGraph+%F0%9F%9A%80;AI+Resume+Checker;Analytics+Dashboard;Skill+Roadmap+Tracker" alt="Typing SVG" />
  </a>
</h1>

<div align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-00C853?style=for-the-badge" />
  &nbsp;
  <img src="https://img.shields.io/badge/Built%20With-MERN%20Stack-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  &nbsp;
  <img src="https://img.shields.io/badge/AI%20Powered-Yes-FF6C37?style=for-the-badge&logo=openai&logoColor=white" />
</div>

<br>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

## 🧠 What is GapGraph?

> **GapGraph** is an all-in-one AI-powered platform designed to help developers, students, and job seekers **identify their gaps, track their growth, and close the distance** between where they are and where they want to be.

It combines three powerful tools under one roof:
- 🤖 **AI Resume Checker** — Get instant AI feedback on your resume
- 📊 **Analytics Dashboard** — Visualize your personal data & growth
- 🗺️ **Skill Roadmap Tracker** — Plan and track your learning journey

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

## ✨ Features

### 🤖 1. AI Resume Checker
- Upload or paste your resume directly into the platform
- AI scores your resume across **5 key categories**:
  - 📝 Clarity & Readability
  - 🔑 Keywords & ATS Optimization
  - 🎨 Formatting & Structure
  - 💥 Impact & Action Verbs
  - 📌 Relevance & Completeness
- Receives an overall **letter grade (A–F)**
- Get **specific, actionable fix suggestions** for each category
- Optionally enter a **target job role** to receive role-tailored feedback
- Side-by-side comparison of **before vs after** improvements

---

### 📊 2. Graph / Analytics Dashboard
- Interactive dashboard to visualize your **personal growth data**
- Supported data sources:
  - 🐙 GitHub activity & contribution stats
  - 📚 Learning progress & course completions
  - 💰 Personal finance tracking
  - 📈 Custom user-uploaded CSV/JSON data
- Features include:
  - Real-time & historical **trend lines**
  - **Filters** by date range, category, and metric
  - Multiple chart types — bar, line, pie, heatmap
  - **Export** charts as PNG or PDF

---

### 🗺️ 3. Skill Roadmap Tracker
- Pick a **learning goal** (e.g. "Become a Full Stack Developer", "Learn DevOps", "Master DSA")
- Get a **curated, step-by-step roadmap** of skills and resources
- Each roadmap node includes:
  - 📖 Recommended free & paid resources
  - ⏱️ Estimated time to complete
  - 🏷️ Difficulty level (Beginner / Intermediate / Advanced)
- **Mark progress** as you go — visualize your % completion
- Track **streaks** and set personal deadlines
- Share your roadmap progress publicly

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

## 🛠️ Tech Stack

**Frontend**
<div align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=000" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Recharts-FF6C37?style=for-the-badge&logo=chartdotjs&logoColor=white" />
</div>

<br>

**Backend**
<div align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
</div>

<br>

**Database & AI**
<div align="left">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
</div>

<br>

**Tools & Deployment**
<div align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

## 🗂️ Project Structure
```
GapGraph/
├── client/                   # React frontend
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Resume, Dashboard, Roadmap pages
│   │   ├── store/            # Redux state management
│   │   └── utils/            # Helper functions & API calls
├── server/                   # Node.js + Express backend
│   ├── controllers/          # Route controllers
│   ├── models/               # MongoDB schemas
│   ├── routes/               # API routes
│   └── middleware/           # Auth & error handling
└── README.md
```

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

## 🚀 Getting Started

### Prerequisites
- Node.js >= 18.x
- MongoDB (local or Atlas)
- OpenAI API Key

### Installation
```bash
# Clone the repository
git clone https://github.com/SwarajPrajapati2006/GapGraph.git
cd GapGraph

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file in the `/server` directory:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
```

### Run the App
```bash
# Run backend (from /server)
npm run dev

# Run frontend (from /client)
npm run dev
```

> App runs on `http://localhost:5173` (frontend) and `http://localhost:5000` (backend)

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

## 🛣️ Roadmap

- [x] Project planning & UI/UX design
- [ ] Authentication (Register / Login / JWT)
- [ ] AI Resume Checker — upload & scoring
- [ ] Analytics Dashboard — charts & filters
- [ ] Skill Roadmap — goal picker & progress tracker
- [ ] GitHub OAuth integration
- [ ] Public roadmap sharing
- [ ] Mobile responsive UI
- [ ] Deployment on Vercel + Render

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

## 👤 Author

**Swaraj Prajapati**
- 🌐 [Portfolio](https://swaraj-portfolio-alpha.vercel.app/)
- 💼 [LinkedIn](https://linkedin.com/in/Swaraj_Prajapati)
- 🐦 [X (Twitter)](https://x.com/Swaraj_06)
- 💻 [GitHub](https://github.com/SwarajPrajapati2006)

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider">
</div>

<div align="center">
  <p><em>⭐ If you like this project, consider giving it a star!</em></p>
  <a href="https://github.com/SwarajPrajapati2006/GapGraph">
    <img src="https://img.shields.io/badge/Star%20This%20Repo-00C853?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</div>

<br>



<img src="https://capsule-render.vercel.app/api?type=waving&color=00C853&height=100&section=footer" width="100%"/>
