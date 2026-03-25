# Cyber Student Portfolio Website Specification

## 1. Project Overview

- **Project Name**: CyberFolio
- **Project Type**: Single-page portfolio website
- **Core Functionality**: A cyber student-themed personal portfolio showcasing academic journey, projects, skills, and achievements - with a tech-savvy student aesthetic
- **Target Users**: Potential employers, internship coordinators, and academic peers

---

## 2. UI/UX Specification

### Layout Structure

**Sections (vertical scroll)**:
1. **Hero Section** - Full viewport with animated network/circuit background, student info, CTA
2. **Skills Section** - Tech skills with animated bars
3. **Experience Section** - Internships, projects, student organizations
4. **Projects Section** - Academic and personal projects
5. **Training Section** - Workshops, courses, certifications in progress
6. **Certifications Section** - Completed certifications
7. **Achievements Section** - Awards, hackathons, competitions
8. **Education Section** - Academic background with CGPA
9. **Contact Section** - Contact form and social links

### Visual Design

**Color Palette (Cyber Student Theme)**:
- `--bg-dark`: #0d1117 (GitHub dark)
- `--bg-secondary`: #161b22 (slightly lighter)
- `--bg-tertiary`: #21262d (card backgrounds)
- `--accent-blue`: #58a6ff (student blue)
- `--accent-green`: #3fb950 (success green)
- `--accent-purple`: #a371f7 (creative purple)
- `--accent-cyan`: #39d4e0 (tech cyan)
- `--text-primary`: #e6edf3 (light text)
- `--text-secondary`: #8b949e (muted text)
- `--border-color`: #30363d (borders)

**Typography**:
- Headings: "JetBrains Mono" (Google Fonts) - coding aesthetic
- Body: "Source Sans 3" (Google Fonts) - readable
- Code: "Fira Code" (Google Fonts)
- Hero Name: 56px desktop, 36px mobile
- Section Titles: 36px desktop, 28px mobile

**Visual Effects**:
- Circuit/network animated background
- Glowing code-style decorations
- Terminal window aesthetic
- Smooth hover transitions
- Scroll-triggered fade animations

### Components

**Navigation**: Fixed, dark with glow on scroll, student-friendly links
**Hero**: Circuit background, coding-focused tagline
**Skills**: Tech stack with proficiency bars
**Experience**: Timeline for internships/jobs
**Projects**: GitHub-style project cards
**Training**: Course cards with progress
**Certifications**: Badge-style display
**Achievements**: Award cards
**Education**: Academic details with CGPA
**Contact**: Terminal-style contact form

---

## 3. File Structure

```
/portfolio
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # All JavaScript
└── README.md           # Deployment instructions
```
