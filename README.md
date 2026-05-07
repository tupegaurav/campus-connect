🎓 Campus Connect — AI-Driven Community & Study Coordination
> An AI-powered student collaboration platform for engineering colleges. Built as a frontend prototype for portfolio demonstration.
![Live Demo](https://YOUR-USERNAME.github.io/campus-connect/)
![PRD](#)
---
📌 Project Overview
Campus Connect addresses a real problem: university students struggle with fragmented communication across WhatsApp, Discord, and Google Drive, leading to poor study group formation and lost academic resources.
This frontend prototype demonstrates the full user journey of the platform, including:
AI Group Matcher — Simulated intelligent peer matching based on courses, goals, and schedule
Smart Resource Hub — Searchable, filterable repository of verified academic materials
Collaboration Board — Real-time group chat workspace with task management
Personalized Dashboard — Activity feed, upcoming sessions, and AI recommendations
3-Step Onboarding — Mobile-first profile setup with preference selection
---
🖥️ Pages
Page	Description
`index.html`	Landing page with feature overview and login
`pages/onboarding.html`	3-step onboarding walkthrough + profile setup
`pages/matcher.html`	AI Group Matcher with simulated peer recommendations
`pages/dashboard.html`	Personalized student dashboard
`pages/resources.html`	Smart Resource Hub with search + upload
`pages/collab.html`	Collaboration Board with group chat + tasks
---
🛠️ Tech Stack
Layer	Technology
Frontend	HTML5, CSS3, Vanilla JavaScript
Fonts	Syne (display), DM Sans (body) via Google Fonts
Deployment	GitHub Pages
Design	Mobile-first, dark theme
Backend (planned)	PHP + MySQL (see PRD)
AI Layer (planned)	Python-based recommendation microservice
---
🚀 Getting Started
Run locally
```bash
git clone https://github.com/YOUR-USERNAME/campus-connect.git
cd campus-connect
# Open index.html in your browser — no build step needed
open index.html
```
Deploy to GitHub Pages
Push this repository to GitHub
Go to Settings → Pages
Under Source, select `main` branch and `/ (root)` folder
Click Save — your site will be live at:
`https://YOUR-USERNAME.github.io/campus-connect/`
---
📱 Features Walkthrough
AI Group Matcher
The hero feature. Click "Run AI Matching" to see a simulated AI loading sequence, followed by 5 peer recommendations with match scores, compatibility tags, and connect actions.
Smart Resource Hub
Browse 12 mock academic resources. Filter by subject, search by keyword, sort by date/saves/verified status. Click Upload to see the upload modal.
Collaboration Board
A three-column layout: group list → chat area → task panel. Type a message and press Enter to send. Check off tasks or add new ones.
Dashboard
Personalized greeting (reads your name from onboarding), live metrics, upcoming sessions, activity feed, and AI recommendation prompts.
---
📂 Project Structure
```
campus-connect/
├── index.html              # Landing + Login
├── css/
│   └── main.css            # Global styles, design tokens
└── pages/
    ├── onboarding.html     # 3-step onboarding
    ├── matcher.html        # AI Group Matcher
    ├── dashboard.html      # Student Dashboard
    ├── resources.html      # Resource Hub
    └── collab.html         # Collaboration Board
```
---
🎯 Product Context
This prototype was built from a full Product Requirements Document (PRD) covering:
Problem landscape and user research
User personas (Anjali — 1st year, Rohit — 4th year)
Feature prioritization (MoSCoW)
Technical architecture and implementation roadmap
Risk analysis and mitigation strategies
Target users: Engineering college students (MIT College of Engineering pilot)
---
🔮 Roadmap
[ ] PHP + MySQL backend integration
[ ] Real AI recommendation engine (Python/scikit-learn)
[ ] Google OAuth login
[ ] Push notifications (Firebase)
[ ] Cloud deployment (AWS / Render)
[ ] Analytics dashboard for faculty
---
👤 Author
Built by [Your Name] as part of a product design and development case study.
💼 LinkedIn
🐙 GitHub
---
Campus Connect · AI-Driven Community & Study Coordination · MIT College of Engineering
