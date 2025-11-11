# Portfolio Setup Guide

Congratulations! Your portfolio website has been created and pushed to GitHub. Follow these steps to complete the setup and customize it.

## 🚀 Step 1: Enable GitHub Pages

1. Go to your repository: https://github.com/MichaelTheAnalyst/MasoodNazari.github.io
2. Click on **Settings** (top right)
3. Scroll down to **Pages** in the left sidebar
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait 2-3 minutes for deployment
7. Your site will be live at: **https://michaeltheanalyst.github.io/MasoodNazari.github.io/**

## ✏️ Step 2: Customize Your Information

### Update Personal Details in `index.html`

Open `index.html` and update:

1. **Your Name and Title** (around line 45-48):
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Your Professional Title</p>
<p class="hero-description">Your tagline or brief description</p>
```

2. **Social Media Links** (around line 55-63):
```html
<a href="https://github.com/YourGitHub" target="_blank">
<a href="https://linkedin.com/in/your-profile" target="_blank">
<a href="mailto:your.email@example.com">
```

3. **About Section** (around line 80-85):
Replace the placeholder text with your actual background and experience.

4. **Contact Section** (around line 196-208):
Update your email and social media links.

### Update Your Skills in `index.html`

Find the Skills section (around line 160-195) and add/remove skills that match your expertise.

## 📁 Step 3: Add Your Projects

You have three options to add your projects:

### Option A: Manual Project Entry

Edit the project cards in `index.html` (around line 105-158):

```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-code"></i> <!-- Choose icon -->
    </div>
    <h3>Your Project Name</h3>
    <p>Description of your project</p>
    <div class="project-tags">
        <span class="tag">Technology 1</span>
        <span class="tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="https://github.com/..." target="_blank">
            <i class="fab fa-github"></i> View Code
        </a>
        <a href="https://..." target="_blank">
            <i class="fas fa-external-link-alt"></i> Live Demo
        </a>
    </div>
</div>
```

### Option B: Use projects.json File

1. Edit `projects.json` with your actual projects
2. Update the project details (title, description, links)
3. The file structure is self-explanatory

### Option C: Automatic GitHub Projects (Recommended)

To automatically load your GitHub repositories:

1. Open `script.js`
2. Find line 73 (at the bottom of the file)
3. Uncomment this line:
```javascript
// loadGitHubProjects();
```
Change to:
```javascript
loadGitHubProjects();
```

This will automatically fetch and display your latest GitHub repositories!

## 📄 Step 4: Update Your CV

Replace the existing CV file:

1. Copy your updated CV to this folder
2. Name it exactly: `Masood Nazari CV.docx` (or update the filename in `index.html`)
3. The download link is already set up in the hero section

## 🎨 Step 5: Customize Colors (Optional)

Want to change the color scheme?

1. Open `styles.css`
2. Find the `:root` section (lines 8-16)
3. Change the color values:

```css
:root {
    --primary-color: #2563eb;     /* Main blue */
    --secondary-color: #1e40af;   /* Darker blue */
    --accent-color: #3b82f6;      /* Light blue */
}
```

You can use any hex color codes you prefer!

## 🖼️ Step 6: Add Your Profile Picture (Optional)

Want to add a profile photo?

1. Add your image file to the project folder (e.g., `profile.jpg`)
2. Open `index.html`
3. Add this code in the hero section before the hero-title:

```html
<div class="profile-image">
    <img src="profile.jpg" alt="Masood Nazari">
</div>
```

4. Add this CSS to `styles.css`:

```css
.profile-image {
    width: 200px;
    height: 200px;
    margin: 0 auto 2rem;
    border-radius: 50%;
    overflow: hidden;
    border: 5px solid rgba(255, 255, 255, 0.3);
}

.profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## 🔄 Step 7: Push Changes to GitHub

After making any changes:

```bash
git add .
git commit -m "Customize portfolio with my information"
git push origin main
```

Wait 1-2 minutes for GitHub Pages to update automatically!

## 📋 Customization Checklist

- [ ] Enable GitHub Pages
- [ ] Update name and title
- [ ] Add your email
- [ ] Update social media links
- [ ] Write about section
- [ ] Add/update skills
- [ ] Add your projects
- [ ] Upload your CV
- [ ] Test on mobile devices
- [ ] Share your portfolio link!

## 🎯 Font Awesome Icons Reference

For project icons, you can use any Font Awesome icon:

- Code: `fa-code`
- Chart: `fa-chart-line`, `fa-chart-bar`
- Database: `fa-database`
- Brain/AI: `fa-brain`
- Mobile: `fa-mobile-alt`
- Web: `fa-globe`, `fa-laptop-code`
- Data: `fa-table`, `fa-file-excel`
- Python: `fa-python`
- JavaScript: `fa-js`

Full list: https://fontawesome.com/v6/search?m=free

## 🆘 Common Issues

### Site not showing up?
- Make sure GitHub Pages is enabled in Settings > Pages
- Wait 2-3 minutes after enabling or pushing changes
- Check that the URL is correct

### Changes not appearing?
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Wait 1-2 minutes after pushing to GitHub
- Check if the changes were actually pushed: `git status`

### Images not loading?
- Make sure image files are in the same folder
- Check file names match exactly (case-sensitive)
- Use relative paths, not absolute paths

## 📱 Testing Your Portfolio

Test your portfolio on:
- Desktop browsers (Chrome, Firefox, Safari, Edge)
- Mobile devices (phone and tablet)
- Different screen sizes

Use Chrome DevTools (F12) to test responsive design!

## 🎉 Next Steps

1. Share your portfolio link with colleagues and on LinkedIn
2. Add it to your email signature
3. Include it on your resume
4. Update it regularly with new projects
5. Monitor visitors using GitHub repository insights

## 📞 Need Help?

If you run into issues:
1. Check the browser console for errors (F12 > Console)
2. Verify all files are properly committed and pushed
3. Review the README.md for additional documentation

---

Good luck with your portfolio! 🚀

