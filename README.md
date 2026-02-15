# Ranim Yasser Mohamed - Portfolio Website

A modern, professional portfolio website showcasing AI Engineering expertise, projects, and skills.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern Aesthetics**: Dark theme with elegant typography and smooth animations
- **Project Showcase**: Detailed presentation of featured AI/ML projects
- **Skills Section**: Comprehensive display of technical skills and expertise
- **Contact Integration**: Direct links to LinkedIn, GitHub, and email

## 📁 Files Included

- `index.html` - Main portfolio webpage (single-file, complete website)
- `profile.jpg` - Your profile photo
- `README.md` - This file with setup instructions

## 🌐 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - For example: `Ranimyassaf.github.io`
4. Set the repository to **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Website (Easiest)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `profile.jpg`
   - `README.md`
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote (replace with your actual URL)
git remote add origin https://github.com/your-username/your-username.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (top right)
3. Scroll down and click "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select `main` and `/ (root)`
6. Click "Save"

### Step 4: Access Your Website

Your website will be live at: `https://your-username.github.io`

It may take 2-5 minutes for the site to deploy the first time.

## 🎨 Customization Guide

### Updating Content

All content is in the `index.html` file. You can edit:

1. **Personal Information**:
   - Search for "Ranim Yasser Mohamed" and update with your name
   - Update the subtitle, description, and about text

2. **Projects**:
   - Each project is in a `<div class="project-card">` section
   - Update project titles, descriptions, tech stacks, and GitHub links

3. **Skills**:
   - Skills are organized in `<div class="skill-category">` sections
   - Add or remove skills by editing the `<span class="skill-tag">` elements

4. **Contact Links**:
   - Update LinkedIn URL in the contact section
   - Update GitHub username link
   - Update email address

### Changing Colors

The color scheme is defined in CSS variables at the top of the file:

```css
:root {
    --primary: #1a1a2e;      /* Main background */
    --accent: #0f4c75;        /* Primary accent color */
    --accent-bright: #3282b8; /* Bright accent color */
    --text: #e8e8e8;          /* Main text color */
    /* ... more colors ... */
}
```

### Updating Profile Photo

Simply replace `profile.jpg` with your new photo (keep the same filename).

## 🔧 Technical Details

- **Single File Design**: Everything is contained in `index.html` for easy deployment
- **No Build Process**: Pure HTML, CSS, and vanilla JavaScript
- **No Dependencies**: All fonts loaded from Google Fonts CDN
- **Fast Loading**: Optimized for performance with minimal external resources

## 📱 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Support

If you encounter any issues:
1. Check that all files are uploaded correctly
2. Ensure GitHub Pages is enabled in repository settings
3. Wait a few minutes for deployment to complete
4. Clear your browser cache and reload

## 📄 License

This portfolio template is free to use and modify for personal use.

---

**Built with passion for showcasing AI Engineering excellence** 🚀
