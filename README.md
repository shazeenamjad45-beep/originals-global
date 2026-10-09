# Originals Global — Official Agency Portfolio Website

Welcome to the repository for **Originals Global** — a modern, responsive digital studio & academic service platform built for international clients.

## 🚀 Built For
- **Core Team**: Shazeen Amjad, Laiba Khalid, and Kinza Khalid.
- **Specializations**: Web Dev, Mobile Apps, UI/UX, 0% Plagiarism Academic Assignments, FYP Capstone, Data Science, Speed Boost, Urgent Bug Fixes.
- **Themes**: Executive Deep Navy & Electric Indigo Dark Theme (with Light Mode support).
- **Navigation**: Dedicated 4-page sequence (`Home` ➔ `Our Team` ➔ `Services` ➔ `Contact Us`) with header routing and pagination controls (`Next` / `Back`).

---

## 📦 File Architecture

```text
Semester 5 BSAI/Software Engneering/
├── index.html        # Main production multi-page web application
├── vercel.json       # Vercel deployment & routing configuration
└── README.md         # Deployment instructions & project summary
```

---

## 🌐 How to Deploy to GitHub & Vercel in 2 Minutes

### Option 1: Deploy via GitHub + Vercel (Recommended)

1. **Initialize Git & Push to GitHub**:
   Open your PowerShell or Command Prompt in this folder and run:
   ```bash
   git init
   git add .
   git commit -m "Deploy Originals Global production web application"
   git branch -M main
   git remote add origin https://github.com/shazeenamjad45-beep/originals-global.git
   git push -u origin main
   ```
   *(Replace the GitHub repository URL with your own repo URL if needed)*.

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
   - Click **Add New...** ➔ **Project**.
   - Import your `originals-global` GitHub repository.
   - Click **Deploy** (No build settings required — Vercel detects `index.html` and `vercel.json` automatically!).
   - Your website will be live at `https://originals-global.vercel.app`!

---

### Option 2: Deploy Directly via Vercel CLI (Instant)

If you have Node.js installed, you can deploy in one command without Git:
```bash
npx vercel
```
Follow the interactive prompts to get your instant live URL!

---

© 2026 **Originals Global**. All rights reserved.
