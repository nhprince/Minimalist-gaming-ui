# Minimalist Gaming UI

A premium gaming aesthetics website featuring Apple-inspired scroll reveal animations and iOS 26 liquid glass effects.

## � Live Demo
**Deployed Site**: https://nhprinceprodhan.dpdns.org/Minimalist-ui/

## �🎨 Features

- **Apple-style Scroll Reveal**: Smooth fade-up animations with staggered delays matching Apple iPhone website
- **iOS 26 Liquid Glass**: Modern glassmorphism effects with blur, borders, and highlights
- **Smooth Scrolling**: Butter-smooth navigation between sections
- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Draggable Elements**: Interactive CTA cards with smooth drag functionality
- **Performance Optimized**: Uses IntersectionObserver for efficient scroll animations

## 🚀 Technologies

- **Tailwind CSS**: Utility-first CSS framework
- **Vanilla JavaScript**: No heavy framework dependencies
- **IntersectionObserver API**: Efficient scroll-triggered animations
- **CSS Custom Properties**: Advanced glassmorphism effects
- **Responsive Grid Layouts**: Flexible column systems

## 📱 Sections

- **Navigation**: Fixed header with glass panel effect
- **Hero**: Full-screen banner with floating CTA card
- **Search**: Interactive search bar with glass styling
- **Store**: Product grid with hover effects
- **Community**: Social media gallery with grayscale hover
- **Catalog**: Product showcase with pricing
- **Your Space**: Feature highlights with glass cards
- **CTA Banner**: Call-to-action with background image

## 🎯 Animation Details

### Scroll Reveal Animation
```css
.reveal {
  opacity: 0;
  transform: translateY(40px);
  transition: opacity 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94),
              transform 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}
.reveal.revealed {
  opacity: 1;
  transform: translateY(0);
}
```

### Staggered Delays
- `.d1` - 0.1s delay
- `.d2` - 0.2s delay  
- `.d3` - 0.3s delay
- `.d4` - 0.4s delay

## 🔧 Installation

```bash
git clone https://github.com/nhprince/Minimalist-gaming-ui.git
cd Minimalist-gaming-ui
```

## 🌟 Credits

Inspired by Apple's iPhone website design language and iOS 26 UI aesthetics.

---

**Minimalist Gaming** - Premium Gaming Aesthetics
