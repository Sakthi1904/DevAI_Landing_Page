# DevAI Landing Page

A modern, responsive landing page for DevAI, featuring a futuristic space theme with smooth animations and interactive elements. Inspired by the animated and futuristic style showcased in the 'Space Education' video from Dribbble.

## 🚀 Features

### Visual & UI Style
- **Futuristic Space Theme**: Dark backgrounds with glowing neon accents (purples, blues, cyans)
- **Smooth Animations**: Scroll-based animations, parallax effects, and section transitions
- **Modern Typography**: Clean, bold typography with emphasis on clarity
- **Interactive Elements**: Animated SVGs, hover effects, and cursor-following animations

### Layout & Responsiveness
- **Fully Responsive**: Seamlessly adapts to mobile, tablet, and desktop
- **Sticky Navigation**: Animated navbar with glowing cursor-follow effect
- **Hero Section**: Animated headline with typewriter effect and CTA buttons
- **Comprehensive Sections**: Features, demo, use cases, testimonials, pricing, and FAQ

### Technical Features
- **Modern CSS**: Custom properties, Grid/Flexbox layouts, advanced animations
- **Vanilla JavaScript**: No framework dependencies, optimized performance
- **Interactive Components**: FAQ accordions, video modals, smooth scrolling
- **Performance Optimized**: Lazy loading, intersection observers, efficient animations

## 🎨 Design System

### Colors
- **Primary Background**: `#0e0e28` (Dark space blue)
- **Secondary Background**: `#1a1a3a` (Darker blue)
- **Primary Accent**: `#7d5fff` (Neon purple)
- **Secondary Accent**: `#00ffd0` (Neon cyan)
- **Text Colors**: White, light gray, and muted variants

### Typography
- **Primary Font**: Inter (Modern, clean)
- **Monospace Font**: JetBrains Mono (For code elements)
- **Font Weights**: 300-800 range for hierarchy

### Animations
- **Smooth Transitions**: 0.15s - 0.5s ease transitions
- **Parallax Effects**: Background elements move at different speeds
- **Hover Effects**: Scale, glow, and color transitions
- **Scroll Animations**: Elements fade in as they enter viewport

## 📁 Project Structure

```
earth/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS styling
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with modern elements
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript (ES6+)**: Modern JS with modules and async/await
- **Font Awesome**: Icons for UI elements
- **Google Fonts**: Inter and JetBrains Mono typography

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. For development, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: 768px - 1024px
- **Large Desktop**: > 1024px

## 🎯 Key Sections

### 1. Hero Section
- Animated background with stars and nebula effects
- Typewriter effect on main headline
- Interactive code editor preview
- Statistics with animated counters

### 2. Features Section
- 6 feature cards with hover animations
- Icon-based design with gradient backgrounds
- Responsive grid layout

### 3. Demo Section
- Video placeholder with modal functionality
- Feature highlights with checkmarks
- Responsive layout

### 4. Use Cases Section
- 4 use case cards for different user types
- Hover effects with accent color transitions
- Icon-based categorization

### 5. Testimonials Section
- 3 testimonial cards with user avatars
- Hover animations and glow effects
- Responsive grid layout

### 6. Pricing Section
- 3 pricing tiers with featured plan
- Hover animations and glow effects
- Responsive design

### 7. FAQ Section
- Interactive accordion functionality
- Smooth expand/collapse animations
- Responsive layout

## 🎨 Customization

### Colors
Modify the CSS custom properties in `styles.css`:
```css
:root {
    --color-bg-primary: #0e0e28;
    --color-primary: #7d5fff;
    --color-accent: #00ffd0;
    /* ... other colors */
}
```

### Animations
Adjust animation timing and effects:
```css
:root {
    --transition-fast: 0.15s ease;
    --transition-normal: 0.3s ease;
    --transition-slow: 0.5s ease;
}
```

### Content
Update the HTML content in `index.html` to match your product:
- Change text content and copy
- Replace placeholder images
- Update links and CTAs
- Modify pricing and features

## 🔧 JavaScript Features

### Interactive Elements
- **Cursor Follower**: Glowing cursor that follows mouse movement
- **Smooth Scrolling**: Navigation links scroll to sections smoothly
- **FAQ Accordion**: Expandable FAQ items with smooth animations
- **Video Modal**: Click to open demo video in modal
- **Counter Animation**: Animated statistics counters
- **Parallax Effects**: Background elements move on scroll

### Performance Optimizations
- **Intersection Observer**: Efficient scroll-based animations
- **Lazy Loading**: Images load only when needed
- **Debounced Events**: Optimized scroll and resize handlers
- **CSS Transforms**: Hardware-accelerated animations

## 🌟 Browser Support

- **Chrome**: 60+
- **Firefox**: 55+
- **Safari**: 12+
- **Edge**: 79+

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support, please open an issue in the repository.

---

**Built with ❤️ for the future of AI-powered development** 