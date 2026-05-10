# OnChain Copilot — Deployment Guide

Built by **Sameer Hassan**, University of Management and Technology, Lahore  
Colosseum Frontier Hackathon 2025

---

## Files in this project

```
index.html       ← Main frontend (upload to GitHub)
vercel.json      ← Vercel config (upload to GitHub)
api/
  chat.js        ← Backend AI proxy (upload to GitHub)
```

---

## Step 1 — Upload to GitHub

1. Go to your existing repo: https://github.com/sameerhassangoraya/onchain-copilot
2. Click **Add file → Upload files**
3. Upload ALL files: `index.html`, `vercel.json`, and the `api` folder with `chat.js`
4. Click **Commit changes**

---

## Step 2 — Deploy to Vercel (for working AI chat)

1. Go to https://vercel.com and sign up free (use GitHub login)
2. Click **Add New Project**
3. Click **Import Git Repository** → select `onchain-copilot`
4. Click **Deploy** (leave all settings default)
5. Go to **Settings → Environment Variables**
6. Add: Name = `ANTHROPIC_API_KEY`, Value = your Claude API key
7. Get your API key free at: https://console.anthropic.com
8. Click **Redeploy** after adding the key

Your live URL: `https://onchain-copilot.vercel.app`

---

## Step 3 — Submit to Colosseum

- **Project Website**: your Vercel URL
- **GitHub**: https://github.com/sameerhassangoraya/onchain-copilot

---

## Note on GitHub Pages

GitHub Pages only serves static HTML — the AI chat `/api/chat` backend won't work there.  
Use **Vercel** for full functionality. GitHub is just for storing the code.
