# ALGO GROUP — Management System

Logistics & Transport internal dashboard for ALGO GROUP.

## 🔐 Login Credentials

| Email | Password | Role |
|-------|----------|------|
| admin@algogroup.us | Algo@2026 | ⚙️ OPS Manager |
| manager@algogroup.us | Support@2026 | 👔 Support Manager |
| sales@algogroup.us | Sales@2026 | 💼 Sales Rep |
| accounting@algogroup.us | Acc@2026 | 📊 Accountant |
| media@algogroup.us | Media@2026 | 📱 Media Manager |
| safety@algogroup.us | Safe@2026 | 🛡️ Safety Officer |

---

## 🚀 Deploy to Vercel via GitHub

### Step 1 — GitHub

1. Go to **github.com** → Sign in
2. Click **New repository** (green button, top right)
3. Name it: `algo-group-dashboard`
4. Set to **Private** ✓
5. Click **Create repository**

Then upload files:
```
Option A — Drag & Drop:
  Click "uploading an existing file" link
  Drag all 3 files: index.html · vercel.json · .gitignore
  Click "Commit changes"

Option B — Git CLI:
  git init
  git add .
  git commit -m "Initial deploy"
  git remote add origin https://github.com/YOUR_USERNAME/algo-group-dashboard.git
  git push -u origin main
```

---

### Step 2 — Vercel

1. Go to **vercel.com** → Sign in with GitHub
2. Click **Add New → Project**
3. Find `algo-group-dashboard` → Click **Import**
4. Framework Preset: **Other** (leave as is)
5. Click **Deploy**

✅ Done! Vercel gives you a live URL like:
`https://algo-group-dashboard.vercel.app`

---

### Step 3 — Custom Domain (optional)

1. In Vercel project → **Settings → Domains**
2. Add: `app.algogroup.us`
3. Follow DNS instructions (add CNAME record in your DNS provider)

---

## 🔑 API Keys (for AI features)

The AI assistant features require an **Anthropic API key**.

1. Go to **console.anthropic.com** → API Keys
2. Create new key
3. In the app, the AI chat will work automatically once the key is set server-side.

> **Note:** For full production use, move the API key to a backend/serverless function.

---

## 📦 Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS (no build step needed)
- **Maps:** Leaflet.js + CartoDB dark tiles
- **AI:** Claude Sonnet API (Anthropic)
- **Deployment:** Vercel (static hosting)
- **Domain:** algogroup.us

---

## 🗂 Files

```
/
├── index.html      ← Main app (single file)
├── vercel.json     ← Vercel deployment config
├── .gitignore      ← Git ignore rules
└── README.md       ← This file
```
