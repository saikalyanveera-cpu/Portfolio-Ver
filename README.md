# Kalyan's Portfolio

A minimal developer portfolio inspired by [abhi.at](https://abhi.at), built with plain HTML/CSS/JS.

## Features
- Dark / Light theme toggle (remembers preference)
- Click avatar to upload your profile photo
- Live clock in nav
- GitHub-style contribution graph
- Fully responsive

---

## 🚀 Deploy to Vercel (Recommended — free, fastest)

### Option A: Drag & Drop (No CLI needed)
1. Go to [vercel.com](https://vercel.com) and sign up with GitHub
2. Click **"Add New Project"** → **"Import"**
3. Drag the entire `portfolio-deploy` folder onto the Vercel dashboard
4. Click **Deploy** — done! You'll get a live URL instantly.

### Option B: Via GitHub
1. Create a new repo on GitHub (e.g. `my-portfolio`)
2. Push these files:
   ```bash
   git init
   git add .
   git commit -m "initial portfolio"
   git remote add origin https://github.com/YOUR_USERNAME/my-portfolio.git
   git push -u origin main
   ```
3. Go to [vercel.com](https://vercel.com) → **"Add New Project"** → import your GitHub repo
4. Click **Deploy** — Vercel auto-detects the static site

### Custom Domain on Vercel
After deploying: **Settings → Domains → Add** your domain (e.g. `kalyan.dev`)

---

## 🐙 Deploy to GitHub Pages (Free)

1. Create a repo named exactly: `YOUR_USERNAME.github.io`
   e.g. `kalyan.github.io`
2. Push the files:
   ```bash
   git init
   git add .
   git commit -m "portfolio"
   git remote add origin https://github.com/kalyan/kalyan.github.io.git
   git push -u origin main
   ```
3. Go to repo **Settings → Pages → Source: main branch → Save**
4. Your site will be live at `https://kalyan.github.io` in ~60 seconds

---

## ✏️ Before You Deploy — Personalize

Open `index.html` and update:

| What | Where to find it |
|------|-----------------|
| GitHub URL | `href="https://github.com/kalyan"` |
| LinkedIn URL | `href="https://linkedin.com/in/kalyan"` |
| Email | `kalyan@email.com` (3 places) |
| Resume PDF | Add your `resume.pdf` to this folder |
| Project links | Each `<a href="#">` in the Projects section |
| Blog links | Each `<div class="blog-item">` |
| Footer quote | Bottom of the file |

---

## 📸 Profile Photo
- Click the avatar on the live site to upload a photo (works in browser)
- To make it permanent: save your photo as `avatar.jpg` in this folder, then change:
  ```html
  <!-- Find this in index.html -->
  <span id="avatar-emoji">🧑‍💻</span>
  
  <!-- Replace with: -->
  <img src="avatar.jpg" alt="Kalyan">
  ```
