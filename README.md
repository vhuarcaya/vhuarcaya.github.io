# Victor Huarcaya - Personal Website

A professional portfolio website for showcasing work in precision optics, space instrumentation, and optical AIV engineering.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to [github.com/new](https://github.com/new)
2. Name your repository: `vhuarcaya.github.io` (or any name you prefer)
3. Make it **Public**
4. Click **Create repository**

### Step 2: Upload Files
1. Click "uploading an existing file"
2. Drag and drop all files from this folder
3. Commit directly to `main` branch

### Step 3: Enable GitHub Pages
1. Go to repository **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Select `main` branch, `/ (root)` folder
4. Click **Save**

Your site will be live at: `https://vhuarcaya.github.io`

## 📁 Site Structure

```
/
├── index.html          # Home page
├── about.html          # About/bio page
├── experience.html     # Career timeline
├── projects.html       # Project portfolio
├── publications.html   # Publications & presentations
├── contact.html        # Contact information
├── css/
│   └── style.css       # All styles
└── assets/
    ├── CV_vhuarcaya.pdf        # Your CV (downloadable)
    └── profile-placeholder.svg  # Replace with your photo
```

## 🖼️ Adding Your Photo

1. Replace `assets/profile-placeholder.svg` with your actual photo
2. Recommended: Name it `profile.jpg` or `profile.png`
3. Update `index.html` line with `id="heroPhoto"`:
   ```html
   <img src="assets/profile.jpg" alt="Victor Huarcaya" id="heroPhoto">
   ```
4. Ideal size: 400x500px or similar portrait orientation

## 🎨 Customization

### Colors
Edit `css/style.css` CSS variables at the top:
```css
:root {
  --accent-primary: #38bdf8;    /* Main accent color */
  --accent-secondary: #818cf8;  /* Secondary accent */
  --bg-primary: #0a0e17;        /* Background */
}
```

### Fonts
The site uses Google Fonts:
- **DM Serif Display** - Headings
- **Source Sans 3** - Body text
- **JetBrains Mono** - Code/technical

### Content
- Update contact info in footer (all pages)
- Modify projects in `projects.html`
- Add/remove publications in `publications.html`

## 🔧 Optional: Custom Domain

To use a custom domain like `victorhuarcaya.com`:

1. Buy domain from Namecheap, Google Domains, etc.
2. In GitHub repo, go to **Settings** → **Pages**
3. Enter your custom domain
4. Configure DNS at your registrar:
   ```
   Type: CNAME
   Name: www
   Value: vhuarcaya.github.io
   ```

## 📝 License

Content © Victor Huarcaya. Code structure free to use.

---

Built with HTML, CSS, and a focus on performance and accessibility.
