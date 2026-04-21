# Onsite Outreach Tool

AI-powered cold outreach email generator for the Onsite Support sales team.

## Deploy to Vercel

### Step 1 — Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ihadriye-ops/onsite-outreach.git
git push -u origin main
```

### Step 2 — Connect to Vercel
1. Go to vercel.com and log in with GitHub
2. Click "Add New Project"
3. Import the `onsite-outreach` repository
4. Click Deploy (default settings are fine)

### Step 3 — Add your API key
1. Go to your project on Vercel → Settings → Environment Variables
2. Add: `ANTHROPIC_API_KEY` = your key (sk-ant-...)
3. Click Save → then Redeploy

Your app will be live at: `https://onsite-outreach.vercel.app`

## Local Development
Open `public/index.html` directly in a browser for UI preview.
For full functionality (API calls), use `vercel dev` with the Vercel CLI.
