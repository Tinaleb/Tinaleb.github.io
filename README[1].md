# Tinale Bradley - Professional Portfolio Website

A modern, responsive portfolio website showcasing security program management expertise, regulatory compliance experience, and professional achievements.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Dark Theme**: Professional dark color scheme with gold accents
- **Animated Elements**: Smooth scroll animations, counter animations, and skill progress circles
- **Interactive Portfolio**: Modal popups for detailed case study views
- **Timeline Experience**: Visual career timeline with hover effects
- **Contact Form**: Integrated contact form with mailto functionality

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right, then **New repository**
3. Name your repository: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
4. Make sure the repository is **Public**
5. Click **Create repository**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop all files from this folder:
   - `index.html`
   - `README.md`
   - `assets/` folder (with your headshot image)
3. Click **Commit changes**

**Option B: Using Git Command Line**
```bash
# Navigate to your portfolio folder
cd portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (tab at the top)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **main** branch
5. Click **Save**
6. Your site will be live at: `https://yourusername.github.io`

## 📁 File Structure

```
portfolio/
├── index.html          # Main website file (all-in-one HTML/CSS/JS)
├── README.md           # This file
└── assets/
    └── img/
        └── headshot.webp   # Your professional headshot
```

## ✏️ Customization Guide

### Update Contact Information

In `index.html`, search for and update:

1. **Email Address** (appears in multiple places):
   - Search for `Tinale.bradley@hotmail.com` - this is already set correctly

2. **Phone Number**:
   - Search for `(570) 994-9654` and update if needed

3. **LinkedIn URL**:
   - Search for `linkedin.com/in/tinalebradley/` and update

4. **GitHub URL**:
   - Search for the GitHub social link and add your profile URL

### Add Resume Download

1. Add your resume PDF to the `assets/` folder (e.g., `assets/TinaleBradley_Resume.pdf`)
2. In `index.html`, find the JavaScript section with `downloadResume` 
3. Replace the alert with:
```javascript
window.open('assets/TinaleBradley_Resume.pdf', '_blank');
```

### Update Headshot Image

1. Replace `assets/img/headshot.webp` with your professional photo
2. Recommended dimensions: 400x480 pixels or similar aspect ratio
3. Supported formats: WebP, PNG, JPG

### Modify Colors

At the top of the `<style>` section, find the `:root` CSS variables:

```css
:root {
    --primary-bg: #0d0d0d;      /* Main background */
    --accent: #FFB800;           /* Gold accent color */
    --text-primary: #FFFFFF;     /* Main text color */
    /* ... more variables ... */
}
```

## 🔧 Technical Details

- **No build process required** - Pure HTML/CSS/JavaScript
- **External dependencies**: 
  - Google Fonts (Outfit, Playfair Display)
  - Font Awesome 6.5.1 (icons)
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## 📱 Responsive Breakpoints

- Desktop: 1024px+
- Tablet: 768px - 1023px
- Mobile: Below 768px

## 🎨 Design Credits

- Inspired by the Tunis Tailwind CSS Portfolio Template
- Custom design and implementation for Tinale Bradley

## 📄 License

This portfolio website is created for Tinale Bradley's personal use.

---

**Questions?** Contact: Tinale.bradley@hotmail.com
