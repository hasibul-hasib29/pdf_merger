# 📄 PDF Merger

A free, private, browser-based PDF merger. Upload multiple PDFs and merge them in upload order. No server, no sign-up — everything runs in your browser.

🔗 **Live Demo**: `https://<your-username>.github.io/pdf-merger/`

## Features

- 🖱️ Drag & drop or click to upload
- 📋 Upload log with file names, sizes, and timestamps
- 🔢 Merges PDFs in exact upload order
- 📊 Progress bar during merge
- 🔒 100% client-side — your files never leave your browser
- 📱 Mobile responsive

## Deploy to GitHub Pages (Free Hosting)

### Step-by-step:

1. **Create a GitHub account** (if you don't have one): [github.com](https://github.com)

2. **Create a new repository**:
   - Go to [github.com/new](https://github.com/new)
   - Name it `pdf-merger`
   - Set it to **Public**
   - Click **Create repository**

3. **Upload the files**:
   - On your new repo page, click **"uploading an existing file"**
   - Drag and drop ALL files and folders from this project
   - Or use git commands (see below)
   - Click **Commit changes**

4. **Enable GitHub Pages**:
   - Go to your repo → **Settings** → **Pages** (left sidebar)
   - Under **Source**, select **GitHub Actions**
   - The workflow will auto-run on your next push

5. **Access your site**:
   - After the action completes (~1 min), visit:
   - `https://<your-username>.github.io/pdf-merger/`

### Using Git (alternative to step 3):

```bash
git clone https://github.com/<your-username>/pdf-merger.git
cd pdf-merger

# Copy all project files here, then:
git add .
git commit -m "Initial commit"
git push origin main
```

## Tech Stack

- Pure HTML/CSS/JS (no frameworks, no build step)
- [pdf-lib](https://pdf-lib.js.org/) for PDF manipulation
- GitHub Actions for deployment

## License

MIT — use it however you want.
