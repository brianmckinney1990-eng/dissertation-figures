# GitHub Pages Setup Guide — Dissertation Figures

## What You'll End Up With
A live site at `https://YOUR-USERNAME.github.io/dissertation-figures/` where your committee and reviewers can view all interactive figures instantly.

---

## Step 1: Create a GitHub Account (skip if you have one)
1. Go to [github.com](https://github.com) and sign up (free)
2. Verify your email

## Step 2: Create a Repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `dissertation-figures`
3. Set to **Public** (required for free GitHub Pages)
4. Check **"Add a README file"**
5. Click **Create repository**

## Step 3: Upload Your Files
1. In your new repo, click **Add file** → **Upload files**
2. Drag in these files:
   - `index.html` (the table of contents page)
   - `john-plutchik.html` (John's Plutchik wheel)
   - *(add more HTML files later as you build them)*
3. Click **Commit changes**

## Step 4: Enable GitHub Pages
1. Go to your repo's **Settings** tab (gear icon)
2. In the left sidebar, click **Pages**
3. Under "Source," select **Deploy from a branch**
4. Set branch to **main** and folder to **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes, then refresh — you'll see a green banner with your live URL

## Step 5: Share
Your site is now live at:
```
https://YOUR-USERNAME.github.io/dissertation-figures/
```

Share this URL with committee members, or link directly to specific figures:
```
https://YOUR-USERNAME.github.io/dissertation-figures/john-plutchik.html
```

---

## Adding New Figures Later
1. Go to your repo on GitHub
2. Click **Add file** → **Upload files**
3. Upload the new HTML file
4. Edit `index.html` to add a new card (copy one of the placeholder blocks, update the href and text)
5. Commit — the site updates automatically in ~1 minute

## File Naming Convention
Use lowercase with hyphens for consistency:
- `john-plutchik.html`
- `john-wave-timeline.html`
- `cross-case-overview.html`
- `abby-plutchik.html`

## Tips
- **Changes are instant**: Edit any file on GitHub, commit, and the site updates within a minute
- **Custom domain** (optional): If you ever want a cleaner URL, GitHub Pages supports custom domains in Settings → Pages
- **No account needed to view**: Anyone with the link can see your figures — no GitHub login required
- **Works everywhere**: Desktop, tablet, phone — the responsive scaling handles it
