# Deploy to GitHub Pages

## Prerequisites
- GitHub account (you already have one — your booking page is at djbenthomas.github.io)

## Steps

### 1. Create a new repo
1. Go to https://github.com
2. Click the **+** icon → **New repository**
3. Name it: **`as-ulikeit`**
4. Make it **Public**
5. Click **Create repository**

### 2. Upload the site files
1. On the new repo page, click **uploading an existing file**
2. Drag and drop the `index.html` file from the `site` folder
3. Scroll down and click **Commit changes**

### 3. Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under "Branch": select **main** and **/(root)**
3. Click **Save**
4. Wait 2 minutes — your site will be live at `https://djbenthomas.github.io/as-ulikeit`

### 4. Point your domain (optional)
If you want as-ulikeit.com to point here instead of Canva:
1. In repo **Settings** → **Pages**, enter `as-ulikeit.com` under Custom domain
2. Go to your domain registrar and add a CNAME record pointing to `djbenthomas.github.io`
