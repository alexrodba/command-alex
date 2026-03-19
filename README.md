# Command.Alex

Your personal life operations dashboard. Deploy it once, use it forever.

## Deploy to GitHub Pages (10 minutes)

### 1. Create a GitHub repo

Go to github.com/new and create a new **public** repo called `command-alex`.

### 2. Push the file

```bash
git init
git add index.html
git commit -m "init"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/command-alex.git
git push -u origin main
```

### 3. Enable GitHub Pages

- Go to your repo → Settings → Pages
- Source: **Deploy from a branch**
- Branch: `main`, folder: `/ (root)`
- Save

Your app will be live at `https://YOUR_USERNAME.github.io/command-alex` in ~60 seconds.

---

## Alternative: Netlify (even faster)

1. Go to [netlify.com](https://netlify.com) and sign up free
2. Drag and drop `index.html` onto the Netlify dashboard
3. Done — you get a URL instantly. You can set a custom subdomain too.

---

## Setup: API Key

The app needs an Anthropic API key to power the AI features (Weekly Plan, AI Analysis, etc).

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Create an account (free tier works fine)
3. Go to API Keys → Create key
4. Open your deployed app → Settings tab → paste the key

The key is stored **only in your browser's localStorage**. It never leaves your device.

**Rough cost:** At personal use levels (a few plan generations per week), you'll spend well under $1/month.

---

## Bookmark it

Once deployed, add it to your phone's home screen:
- **iPhone**: Open in Safari → Share → Add to Home Screen
- **Android**: Open in Chrome → Menu → Add to Home Screen

---

## Updating the app

If you want to make changes, edit `index.html` and push to GitHub — Pages redeploys automatically.

```bash
git add index.html
git commit -m "update"
git push
```
# command-alex
My dashboard
