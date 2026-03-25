# Cyber Student Portfolio

A clean, developer-focused portfolio website with animations, built with HTML, CSS, and JavaScript. Ready to deploy on GitHub Pages.

![Portfolio](https://img.shields.io/badge/Student-Portfolio-58a6ff?style=for-the-badge)

## ✨ Features

- **Developer Aesthetic**: Clean, GitHub-inspired dark theme
- **Network Animation**: Animated node connections background
- **Scroll Animations**: Smooth fade-in effects
- **Skill Bars**: Animated progress indicators
- **Responsive Design**: Works on all devices
- **Code-First Design**: Monospace fonts, terminal-inspired elements

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # All JavaScript
└── README.md           # This file
```

## 🎨 Tech Stack

- HTML5
- CSS3 (Variables, Grid, Flexbox)
- JavaScript (Vanilla)
- Google Fonts (JetBrains Mono, Source Sans 3, Fira Code)

## 🛠️ Customization

### 1. Update Personal Information

Edit `index.html`:

- **Name**: Find "Your Name" in the hero section
- **Tagline**: Update the tagline text
- **Email**: Change in the contact section
- **Social Links**: Update href attributes

### 2. Update Skills

Modify skill percentages in HTML:

```html
<div class="skill-item">
    <span class="skill-name">JavaScript</span>
    <div class="skill-bar"><div class="skill-progress" data-width="90"></div></div>
    <span class="skill-level">90%</span>
</div>
```

Change `data-width` to set the percentage (0-100).

### 3. Update Experience

Edit timeline items in the experience section with your internships, jobs, or activities.

### 4. Update Projects

Modify project cards with your GitHub repositories:

- Update project title and description
- Add GitHub and live demo links
- List technologies used

### 5. Update Training & Certifications

Add courses and certifications you're currently taking or have completed.

### 6. Update Achievements

Add awards, hackathon wins, or other accomplishments.

### 7. Update Education

Edit your academic details with CGPA/percentage.

## 🚀 Deployment to GitHub Pages

### Option 1: Using GitHub UI

1. **Create a Repository**:
   - Go to [GitHub](https://github.com)
   - Click "New repository"
   - Name it `portfolio` or your preferred name
   - Select "Public"
   - Click "Create repository"

2. **Upload Files**:
   - Click "Upload an existing file"
   - Drag and drop all files from your `portfolio` folder
   - Commit changes

3. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Under "Branch", select "main" (or "master")
   - Click "Save"
   - Wait 1-2 minutes

4. **Access Your Site**:
   - Your site will be at: `https://yourusername.github.io/portfolio/`

### Option 2: Using Git Commands

```bash
# Clone your repository
git clone https://github.com/yourusername/portfolio.git

# Navigate to the folder
cd portfolio

# Add files
git add .

# Commit
git commit -m "Initial commit"

# Push to GitHub
git push origin main

# Enable GitHub Pages in settings
```

## 🎯 Color Scheme

| Color | Hex | Usage |
|-------|-----|-------|
| Dark Background | `#0d1117` | Main bg |
| Secondary BG | `#161b22` | Cards |
| Accent Blue | `#58a6ff` | Links, highlights |
| Accent Green | `#3fb950` | Success |
| Accent Purple | `#a371f7` | Gradients |
| Text Primary | `#e6edf3` | Main text |
| Text Secondary | `#8b949e` | Muted text |

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px

## 🐛 Troubleshooting

### Page Not Found
- Check that `index.html` is in the root directory
- Verify GitHub Pages branch is set correctly

### Styles Not Loading
- Ensure `css/style.css` path is correct in HTML

### Animations Not Working
- JavaScript must be enabled
- Check browser console for errors

## 🤝 Contributing

Feel free to fork and customize!

## 📄 License

MIT License - Use freely.

---

**Built with** 💻 by a fellow student
