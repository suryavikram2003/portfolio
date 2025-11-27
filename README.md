# 🚀 Portfolio Website

A modern, responsive, and fully customizable portfolio website built with HTML, CSS, and JavaScript. Ready to deploy on GitHub Pages, Vercel, or Netlify.

![Portfolio Preview](https://via.placeholder.com/1200x630/6366f1/ffffff?text=Portfolio+Website)

## ✨ Features

- **Responsive Design** - Mobile-first approach, works on all devices
- **Dark Mode** - Toggle between light and dark themes
- **Smooth Animations** - CSS animations and scroll effects
- **Contact Form** - Client-side validation ready for backend integration
- **SEO Optimized** - Meta tags, Open Graph, and structured data
- **Accessibility** - ARIA labels and semantic HTML
- **Fast Loading** - Optimized CSS and JavaScript
- **Easy Customization** - Well-commented code for easy modifications

## 📋 Sections

1. **Hero/Landing** - Eye-catching introduction with typing animation
2. **About** - Biography and personal information
3. **Skills** - Technical skills with icons
4. **Projects** - Portfolio showcase with links
5. **Contact** - Contact form and social links

## 🛠️ Technology Stack

- HTML5 (Semantic markup)
- CSS3 (Custom properties, Flexbox, Grid)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- No external frameworks required

## 🚀 Live Demo

[View Live Demo](https://suryavikram2003.github.io/portfolio/)

## 📦 Quick Start

### Option 1: Clone the Repository

```bash
git clone https://github.com/suryavikram2003/portfolio.git
cd portfolio
```

### Option 2: Download ZIP

Download the ZIP file from the repository and extract it.

### Local Development

Open `index.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository **Settings** → **Pages**
3. Select **Source**: Deploy from a branch
4. Select **Branch**: `main` (or `master`) and folder: `/ (root)`
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io/portfolio/`

### Vercel

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com) and sign in
3. Click **Add New** → **Project**
4. Import your repository
5. Click **Deploy**
6. Your site will be live at `https://your-project.vercel.app`

### Netlify

1. Push your code to GitHub
2. Go to [netlify.com](https://netlify.com) and sign in
3. Click **Add new site** → **Import an existing project**
4. Connect to GitHub and select your repository
5. Click **Deploy site**
6. Your site will be live at `https://your-site.netlify.app`

## 🎨 Customization Guide

### Personal Information

Edit `index.html` to update:

```html
<!-- Hero Section -->
<h1 class="hero-title">Your Name</h1>

<!-- About Section -->
<p>Your biography goes here...</p>

<!-- Contact Section -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
```

### Typing Animation

Edit `js/script.js` to change the typing words:

```javascript
const CONFIG = {
    typingWords: [
        'Full Stack Developer',
        'Your Role 1',
        'Your Role 2'
    ]
};
```

### Social Media Links

Find and update these throughout `index.html`:

```html
<a href="https://github.com/your-username">GitHub</a>
<a href="https://linkedin.com/in/your-profile">LinkedIn</a>
<a href="https://twitter.com/your-handle">Twitter</a>
```

### Projects

Add or modify projects in the Projects section of `index.html`:

```html
<article class="project-card">
    <div class="project-image">
        <img src="images/your-project.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
        </div>
    </div>
</article>
```

### Skills

Modify skills in the Skills section:

```html
<div class="skill-item">
    <i class="fab fa-your-icon"></i>
    <span>Your Skill</span>
</div>
```

Find icons at [Font Awesome](https://fontawesome.com/icons).

### Colors

Edit CSS custom properties in `css/style.css`:

```css
:root {
    --primary-color: #6366f1;  /* Main accent color */
    --secondary-color: #10b981; /* Secondary accent */
    --text-color: #1f2937;      /* Main text */
    --bg-color: #ffffff;        /* Background */
}
```

### Resume/CV

Add your resume link:

```html
<a href="path/to/your-resume.pdf" class="btn btn-primary" download>
    <i class="fas fa-download"></i> Download Resume
</a>
```

### Contact Form Backend

The form is ready for integration. Options include:

**Formspree:**
```html
<form action="https://formspree.io/f/your-id" method="POST">
```

**Netlify Forms:**
```html
<form name="contact" netlify>
```

**Custom Backend:**
```javascript
contactForm.addEventListener('submit', async (e) => {
    e.preventDefault();
    const formData = new FormData(contactForm);
    await fetch('your-api-endpoint', {
        method: 'POST',
        body: formData
    });
});
```

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles (responsive, dark mode)
├── js/
│   └── script.js       # JavaScript functionality
├── images/
│   └── .gitkeep        # Placeholder for images
├── README.md           # Documentation
├── vercel.json         # Vercel configuration
├── netlify.toml        # Netlify configuration
├── robots.txt          # SEO robots file
├── sitemap.xml         # SEO sitemap
└── .gitignore          # Git ignore rules
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🔧 Performance Tips

1. **Optimize Images**: Compress images before adding
2. **Use WebP**: Convert images to WebP format
3. **Lazy Loading**: Add `loading="lazy"` to images
4. **Minify**: Minify CSS/JS for production

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👤 Author

**Surya Vikram**

- GitHub: [@suryavikram2003](https://github.com/suryavikram2003)

---

⭐ Star this repo if you find it helpful!
