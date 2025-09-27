# Edunet Foundation — Online Quiz Application

**Project overview**  
This is a lightweight, mobile-friendly Online Quiz Application built as a small but polished submission for my internship. It’s designed for students and educators to practice and test knowledge with multiple-choice questions, timers, instant feedback and a local leaderboard. The UI is simple, responsive and visually appealing so it stands out without being heavyweight.

**Presented by**  
- **Student:** Vishnu Vardhan Reddy Dumpa  
- **College:** Parul University  
- **Department:** CSE — Cyber Security  
- **Email:** vishnureddyvs1@gmail.com  
- **AICTE Student ID:** STU6565b6fbca7aa1701164795

## Features
- Single-page quiz experience with one question at a time.  
- Per-question timer and immediate feedback (correct / incorrect).  
- Progress bar and smooth transitions between questions.  
- Final score summary with percentage and encouraging message.  
- Local leaderboard using `localStorage` (keeps recent scores).  
- Responsive layout — works well on phones and desktops.  
- Clean, well-commented code split into `index.html`, `style.css` and `script.js` (or a React + Vite setup if you prefer).

## Tech stack
A small, focused stack so the app is easy to run and submit:
- HTML, CSS, JavaScript (vanilla) — or TypeScript + React / Vite (project files include a modern setup).  
- Optional: Tailwind CSS for quick styling (config included).  
- Local JSON question store, `localStorage` for leaderboard.

## How to run ( HTML/CSS/JS)
1. Clone the repo or copy the project folder to your machine.  
2. Open `index.html` in your browser (double-click or serve with a simple HTTP server).  
3. Start a quiz and follow on-screen instructions.

npm install
npm run dev
.
├─ index.html
├─ style.css
├─ script.js
├─ data/
│  └─ questions.json
├─ public/ (icons, favicon)
└─ README.md 

If using the included React + Vite setup, the src/ folder contains components and styles.
Notes on design decisions
Kept the UI minimal so the app is lightweight and loads fast.
Timer logic and scoring are intentionally simple and deterministic so testing is straightforward.
Leaderboard is local to avoid extra backend work for the submission — easy to extend to a server if required.

How I tested it
Manual tests on desktop and mobile (Chrome/Firefox).
Verified timer behaviour, score calculation and local leaderboard persistence.
Ensured keyboard accessibility for basic actions.
Future improvements (optional)
Real-time multiplayer quizzes using Socket.IO or Firebase.
CSV/JSON import for educators and IndexedDB support for larger question banks.
Exportable results and simple analytics dashboard.

Licence
This project is submitted as part of an internship requirement. You are free to view and run the code for evaluation. If you reuse it, please credit the author.

Contact
**If you need any clarifications or want to see additional features, email me: vishnureddyvs1@gmail.com**
**Good luck with the submission — I built this to be small, reliable and visually neat so it makes a good impression**

### .gitignore
```gitignore
# Node & npm
node_modules/
npm-debug.log*
yarn-debug.log*
yarn-error.log*
package-lock.json
pnpm-lock.yaml
bun.lockb

# Vite / build output
dist/
build/
.vite/

# TypeScript
*.tsbuildinfo
*.d.ts
tsconfig.tsbuildinfo

# Logs
logs/
*.log

# IDEs and editors
.vscode/
.idea/
*.sublime-workspace
*.sublime-project

# Mac / Windows
.DS_Store
Thumbs.db

# Local environment files
.env
.env.local
.env.*.local

# Test / coverage
coverage/
*.lcov

# Misc
public/favicon.ico
public/placeholder.svg
