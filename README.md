# JARVIS — Personal AI Assistant
### Deploy in 10 minutes. Free forever.

---

## What you need
- GitHub account → github.com/signup
- Vercel account → vercel.com/signup (connect with GitHub)
- Anthropic API key → console.anthropic.com → API Keys → Create Key

---

## Step 1 — Upload to GitHub

1. Go to github.com → click **"New repository"**
2. Name it `jarvis-ai` → click **"Create repository"**
3. Click **"uploading an existing file"**
4. Drag and drop ALL these files maintaining the folder structure:
   ```
   api/chat.js
   public/index.html
   public/manifest.json
   vercel.json
   package.json
   ```
5. Click **"Commit changes"**

---

## Step 2 — Deploy to Vercel

1. Go to vercel.com → click **"Add New Project"**
2. Click **"Import"** next to your `jarvis-ai` repository
3. Leave all settings as default → click **"Deploy"**
4. Wait ~60 seconds → Vercel gives you a URL like `jarvis-ai-abc123.vercel.app`

---

## Step 3 — Add your API Key (IMPORTANT)

1. In Vercel dashboard → go to your project → **Settings** → **Environment Variables**
2. Click **"Add New"**
   - Name: `ANTHROPIC_API_KEY`
   - Value: `sk-ant-...` (paste your key from console.anthropic.com)
3. Click **Save**
4. Go to **Deployments** → click **"Redeploy"** on the latest deployment

---

## Step 4 — Access JARVIS anywhere

Your JARVIS is now live at your Vercel URL.

### Add to Android Home Screen (feels like an app):
1. Open Chrome on your phone
2. Go to your Vercel URL
3. Tap ⋮ menu → "Add to Home Screen"
4. JARVIS icon appears on your home screen

### Add to iPhone Home Screen:
1. Open Safari on iPhone
2. Go to your Vercel URL
3. Tap Share button → "Add to Home Screen"

---

## Cost
- Vercel: **Free** (100GB bandwidth/month, more than enough)
- Anthropic API: **Free credits** on signup (~$5 worth), then pay-as-you-go
  - Each JARVIS conversation costs roughly $0.001–0.003 per message
  - Very cheap for daily personal use

---

## Updating JARVIS later
1. Edit files on GitHub directly (click the file → pencil icon)
2. Vercel auto-redeploys within 60 seconds

---

Built with Claude · Powered by Anthropic API · Hosted on Vercel
