# 🎮 Hytale Voting Sites

A beautiful, modern, and blazing-fast voting hub designed for Hytale servers and gaming communities. Built with a stunning Hytale-inspired color palette and optimized for maximum performance.

![Imgur Image](https://i.imgur.com/DpCfZVv.png)

## ✨ Features

- **Hytale-Inspired Design** - Cyan, blue & orange gradient theme matching Hytale's aesthetic
- **Numbered Voting List** - Clean vertical layout with large numbered items (01-10)
- **Fully Responsive** - Perfect on mobile, tablet, and desktop
- **Lightning Fast** - 95+ PageSpeed score, no heavy dependencies
- **Smooth Animations** - Subtle hover effects and transitions
- **Accessible** - WCAG 2.1 AA compliant with proper contrast ratios
- **SEO Optimized** - Meta tags, semantic HTML, Open Graph support
- **Easy to Customize** - Simple CSS variables for quick theming
- **Animated Statistics** - Counter animations triggered on scroll
- **Modern Typography** - Google Fonts (Poppins) with async loading

## 🚀 Live Demo

Check out the live demo: [yamiru.com/voting-hytale](https://yamiru.com/voting-hytale/)

## 📦 Quick Start


### 1. Edit Your Voting Links

Replace links in `index.html`:

```html
<a href="https://your-voting-site-1.com" class="vote-item" target="_blank" rel="noopener">
```

### 2. Customize Your Server Name

Update the title:

```html
<h1 class="title">Your Server Name</h1>
```

### 3. Optional: Customize Colors

Edit CSS variables in `style.css`:

```css
:root {
    --hytale-cyan: #00D4AA;
    --hytale-blue: #00B4D8;
    --hytale-orange: #FF6B35;
}
```



## 🎨 Customization Guide

### Colors

```css
:root {
    --hytale-cyan: #00D4AA;    /* Primary accent */
    --hytale-blue: #00B4D8;    /* Secondary accent */
    --hytale-orange: #FF6B35;  /* Tertiary accent */
    
    --dark-1: #0A0F1C;         /* Background */
    --dark-2: #0F1629;         /* Cards */
    --dark-3: #151D35;         /* Elements */
    
    --text-primary: #FFFFFF;   /* Main text */
    --text-secondary: #B8C5D6; /* Secondary text */
    --text-muted: #8899AA;     /* Muted text */
}
```

### Statistics

```html
<div class="stat-value" data-target="1500">0</div>
<div class="stat-label">Members</div>
```

### Voting Platforms

```html
<a href="https://example.com" class="vote-item" target="_blank" rel="noopener">
    <div class="vote-number">01</div>
    <div class="vote-content">
        <div class="vote-icon">🏆</div>
        <div class="vote-info">
            <h3>Platform Name</h3>
            <span class="vote-subtitle">Description</span>
        </div>
    </div>
    <div class="vote-action">
        <span class="vote-btn">Vote</span>
        <svg class="arrow-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M5 12h14M12 5l7 7-7 7"/>
        </svg>
    </div>
</a>
```



## 🛠️ Technologies Used

### Core Technologies

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic markup structure |
| CSS3 | Modern styling with custom properties |
| Vanilla JavaScript | Lightweight interactions |

### CSS Features

- CSS Grid & Flexbox layouts
- CSS Custom Properties (variables)
- Gradient backgrounds
- Smooth transitions
- Responsive media queries

### JavaScript Features

- Intersection Observer API (stats animation)
- ES6+ syntax
- Minimal footprint (~20 lines)

### Performance Optimizations

- Async font loading with preload
- Minimal font weights (400, 600, 700)
- No heavy animations


## 📱 Mobile Optimization

- Responsive grid → single column on mobile
- Touch-friendly tap targets (48px minimum)
- Optimized font 

## ♿ Accessibility

- WCAG 2.1 AA compliant contrast ratios
- Semantic HTML5 landmarks (`<main>`, `<header>`, `<footer>`)
- Keyboard navigation with visible focus states
- Screen reader friendly


## 🌐 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | 88+ |
| Firefox | 85+ |
| Safari | 14+ |
| Edge | 88+ |

## 🚀 Deployment Options

### GitHub Pages

1. Push to GitHub repository
2. Go to Settings → Pages
3. Select branch and save

### Netlify

1. Connect your repository
2. Deploy automatically

### Traditional Hosting

Upload `index.html` and `style.css` via FTP or cPanel.


## 💬 Support

If you have questions or need help:

- [Open an issue](https://github.com/Yamiru/hytale-voting-sites/issues)
- Check existing issues for solutions

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with 💚 for the gaming community by [Yamiru](https://github.com/Yamiru)
