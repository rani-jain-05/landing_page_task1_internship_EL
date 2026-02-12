# landing_page_task1_internship_EL
Modern responsive landing page built with HTML &amp; CSS featuring wave design, animations, and mobile-friendly layout using Flexbox and media queries.
# Project_Palette- Unique Responsive Landing Page

## 🎨 What Makes This Different

This landing page breaks away from typical designs with these unique features:

### 1. **Diagonal & Asymmetric Layouts**
- Floating animated cards with rotation effects
- Asymmetric grid layout instead of traditional centered design
- Angular geometric shapes in the background

### 2. **Bold Typography Mix**
- Combines modern sans-serif (Space Grotesk) with elegant serif (Playfair Display)
- Gradient text effects on key elements
- Oversized hero titles with staggered animation

### 3. **Animated Background System**
- Organic morphing shapes that float across the screen
- Subtle gradients creating depth
- Non-distracting ambient motion

### 4. **Modern Color Palette**
- Deep navy/slate background (#020617)
- Vibrant indigo-to-pink gradients
- High contrast for accessibility

### 5. **Interactive Elements**
- Cards that float and respond to hover
- Smooth scroll indicators
- Dynamic header that changes on scroll
- Glassmorphism effects (backdrop blur)

### 6. **Advanced CSS Techniques**
- CSS Grid for complex layouts
- Custom CSS properties (variables) for theming
- Keyframe animations for organic movement
- Clip-path gradients for unique effects

## 🚀 Setup Instructions

### Option 1: Using Live Server (VS Code)

1. Install the "Live Server" extension in VS Code
2. Open the project folder in VS Code
3. Right-click on `index.html`
4. Select "Open with Live Server"
5. Your browser will open automatically at `http://127.0.0.1:5500`

### Option 2: Using Python

```bash
# Navigate to the project folder
cd path/to/project

# Start a simple HTTP server
python -m http.server 8000

# Open browser to http://localhost:8000
```

### Option 3: Direct File Opening

Simply double-click `index.html` to open in your browser (some features may not work)

## 📱 Testing Responsiveness

### In Chrome DevTools:
1. Press `F12` or `Ctrl+Shift+I` (Windows) / `Cmd+Option+I` (Mac)
2. Click the device toolbar icon (or press `Ctrl+Shift+M`)
3. Test different screen sizes:
   - Desktop: 1920x1080
   - Tablet: 768x1024
   - Mobile: 375x667

### Breakpoints Used:
- **Desktop**: > 1024px - Full grid layout with floating cards
- **Tablet**: 768px - 1024px - Stacked hero, simplified grid
- **Mobile**: < 768px - Single column, hamburger menu
- **Small Mobile**: < 480px - Optimized for tiny screens

## 🎯 Key Features Demonstrated

### HTML Structure
✅ Semantic HTML5 elements
✅ Proper document structure
✅ Accessibility attributes (aria-label)
✅ SEO-friendly structure

### CSS Techniques
✅ CSS Grid for complex layouts
✅ Flexbox for component alignment
✅ Custom properties (CSS variables)
✅ Keyframe animations
✅ Media queries for responsive design
✅ Pseudo-elements (::before, ::after)
✅ Transform and transition effects
✅ Gradient effects
✅ Backdrop filters

### JavaScript Functionality
✅ Mobile menu toggle
✅ Smooth scrolling
✅ Scroll-triggered header effects
✅ Intersection Observer API
✅ Event listeners

## 🎨 Customization Guide

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --color-primary: #6366f1;    /* Main brand color */
    --color-accent: #ec4899;     /* Accent color */
    --color-bg: #020617;         /* Background */
}
```

### Typography
Change fonts by updating the Google Fonts link in `index.html` and variables in `style.css`

### Content
Update text in `index.html` - all content is clearly structured

## 📂 File Structure

```
project/
│
├── index.html      # Main HTML structure
├── style.css       # All styling and animations
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🌟 Unique Design Elements

1. **Geometric Logo**: Triangle symbol (◢) used as brand icon
2. **Status Indicator**: Animated pulsing dot showing availability
3. **Floating Stats Cards**: Three cards with different rotation angles
4. **Gradient Buttons**: Smooth hover effects with shadows
5. **Scroll Indicator**: Animated line guiding users
6. **Glassmorphism Footer**: Semi-transparent with blur effect

## 📝 Learning Outcomes

After completing this project, you'll understand:
- How to structure a professional landing page
- CSS Grid vs Flexbox usage
- Creating smooth animations
- Mobile-first responsive design
- Modern CSS techniques (custom properties, backdrop-filter)
- JavaScript DOM manipulation
- Intersection Observer API

## 🔧 Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support (iOS 14+)
- Opera: ✅ Full support

## 💡 Tips

1. **Performance**: All animations use CSS transforms for better performance
2. **Accessibility**: High contrast ratios, semantic HTML, keyboard navigation
3. **SEO**: Proper heading hierarchy, meta tags, semantic structure
4. **Maintainability**: CSS variables make theme changes easy

---

Built with ❤️ using modern web technologies
