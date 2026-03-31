# Property Deal Pipeline — Web App

A two-page web app for managing property acquisition leads with your birddog team.

## Files

| File | Purpose | Who sees it |
|------|---------|-------------|
| `submit-lead.html` | Public birddog submission form | Birddogs — share this URL |
| `pipeline-private.html` | Private deal pipeline dashboard | You only — never share |

## Live URLs (after deploying)

- **Birddog submit page:** `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/submit-lead.html`
- **Your private pipeline:** `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/pipeline-private.html`

---

## Deploy to GitHub Pages (free, 5 minutes)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up for free if you don't have one.

### Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it something like `deal-pipeline`
3. Set it to **Public** *(required for free GitHub Pages)*
4. Click **Create repository**

### Step 3 — Upload your files
1. On your new repo page, click **uploading an existing file**
2. Drag and drop both HTML files:
   - `submit-lead.html`
   - `pipeline-private.html`
3. Scroll down, click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** (top of your repo)
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main` / Folder: `/ (root)`
5. Click **Save**

### Step 5 — Get your URLs
After about 60 seconds, your site will be live at:
```
https://YOUR-USERNAME.github.io/deal-pipeline/
```

Share `submit-lead.html` URL with birddogs. Keep `pipeline-private.html` URL private.

---

## Email Alerts Setup

Notification email is pre-configured to: **forwillenterprises@gmail.com**

Alerts are sent via Claude's Gmail integration when:
- You import a pending submission in the pipeline dashboard
- You add a lead manually
- You click "Resend alert" on any lead

---

## Google Sheets Auto-Sync (optional)

1. Go to [console.cloud.google.com](https://console.cloud.google.com)
2. Create a project → Enable **Google Sheets API**
3. Go to **Credentials** → **Create API Key**
4. Open `pipeline-private.html` → **Settings** → paste the key
5. Click **Sync Sheets** — it auto-creates a new sheet and writes all leads

After first sync, the Sheet ID is saved. Every future sync updates the same sheet.

---

## Updating files later

To update either file after changes:
1. Go to your GitHub repo
2. Click the file name
3. Click the **pencil icon** (Edit)
4. Paste updated content
5. Click **Commit changes** — live in ~30 seconds

---

*Built for ForWill Enterprises | forwillenterprises@gmail.com*
