# Barca Koseoglu - Personal Website

A multi-page personal website built with HTML, CSS, and JavaScript. Ready to host on [GitHub Pages](https://pages.github.com/).

## Pages

| Page | File | Description |
|------|------|-------------|
| **Home** | `index.html` | Bio, introduction, contact info, resume download |
| **Education** | `education.html` | Schools, degrees, GPA, coursework |
| **Experience** | `experience.html` | Research experience and work history |
| **Certifications** | `certifications.html` | Professional certifications |
| **Activities** | `activities.html` | Extracurriculars, volunteering, leadership |
| **Skills** | `skills.html` | Programming languages, tools, expertise |
| **Portfolio** | `portfolio.html` | Projects showcase (empty template ready to fill) |

## File Structure

```
personal-website/
├── index.html              # Home / Bio page
├── education.html          # Education page
├── experience.html         # Experience page
├── certifications.html     # Certifications page
├── activities.html         # Activities page
├── skills.html             # Skills page
├── portfolio.html          # Portfolio page (empty, ready to populate)
├── css/
│   └── style.css           # Shared stylesheet
├── js/
│   └── main.js             # Shared JavaScript (mobile nav)
├── assets/
│   └── resume.pdf          # Your resume
└── README.md               # This file
```

## Hosting on GitHub Pages

1. Create a repository named `Barca-Koseoglu.github.io`
2. Upload all files to the repository
3. Go to **Settings &rarr; Pages**
4. Select source: **Deploy from a branch**
5. Choose branch: `main`, folder: `/ (root)`
6. Your site will be live at `https://barca-koseoglu.github.io`

## Adding Projects to Portfolio

Open `portfolio.html` and replace the empty placeholder with project cards using this template:

```html
<div class="portfolio-card">
    <div class="portfolio-header">
        <h2>Project Name</h2>
        <span class="portfolio-tag">Python</span>
    </div>
    <p class="portfolio-date">Month Year</p>
    <p class="portfolio-desc">
        Description of what the project does, technologies used, and what you learned.
    </p>
    <div class="portfolio-links">
        <a href="https://github.com/..." target="_blank" class="portfolio-link">GitHub &rarr;</a>
        <a href="https://..." target="_blank" class="portfolio-link">Live Demo &rarr;</a>
    </div>
</div>
```

## Customization

- **Colors**: Edit CSS variables at the top of `css/style.css`
- **Content**: Edit the HTML files directly — each page is self-contained
- **Resume**: Replace `assets/resume.pdf` with your latest version

## Features

- Fully responsive design
- Sticky navigation bar
- Mobile hamburger menu
- Clean, recruiter-friendly layout
- No dependencies or build step required
