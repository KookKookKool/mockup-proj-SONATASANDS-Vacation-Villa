# 🏖️ Sonata Sands - Luxury Vacation Villa Website

A modern, elegant single-page website showcasing luxury vacation villas in Krabi, Thailand. Features smooth GSAP animations, responsive design, and a sophisticated "Sand Tone" color palette.

![Sonata Sands Preview](https://images.unsplash.com/photo-1499793983690-e29da59ef1c2?q=80&w=2070)

## ✨ Features

- **🎨 Elegant Design**: Sand tone color palette with warm whites and palm greens
- **🎬 Smooth Animations**: GSAP ScrollTrigger effects throughout
- **📱 Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **🖼️ Image Gallery**: Masonry layout with video integration
- **📝 Contact Form**: Inquiry form for booking requests
- **🗺️ Interactive Map**: Embedded Google Maps location
- **⭐ Reviews Section**: Customer testimonials with ratings
- **📰 Journal/Blog**: Article cards with hover effects

## 🏗️ Sections

1. **Navigation** - Fixed navbar with scroll effects
2. **Hero** - Full-screen hero with parallax effect
3. **Overview** - Property introduction with image stack
4. **Villa Types** - Two accommodation options with detailed features
5. **Gallery** - Masonry grid with images and video
6. **Facilities** - Curated amenities showcase
7. **Reviews** - Guest testimonials
8. **Journal** - Lifestyle articles
9. **Location** - Map with location details
10. **Contact** - Booking inquiry form
11. **Footer** - Contact information and social links

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox
- **JavaScript** - Vanilla JS for interactions
- **[GSAP 3.12.5](https://greensock.com/gsap/)** - Animation library
- **[ScrollTrigger](https://greensock.com/scrolltrigger/)** - Scroll-based animations
- **[Font Awesome 6.0.0](https://fontawesome.com/)** - Icons
- **[Google Fonts](https://fonts.google.com/)** - Typography (Allura, Cormorant Garamond, Montserrat, Playfair Display)

## 🎨 Design System

### Color Palette
```css
--bg-primary: #FDFBF7    /* Warm white background */
--bg-sand: #F4F1EA       /* Sand tone */
--text-main: #594A3C     /* Dark brown text */
--text-gold: #9C8C74     /* Gold accents */
--text-muted: #7A7570    /* Muted text */
--accent-green: #4F634D  /* Palm green */
--accent-dark: #1a1a1a   /* Dark footer */
```

### Typography
- **Headers**: Cormorant Garamond (Serif, Bold, Uppercase)
- **Script**: Allura (Cursive)
- **Body**: Montserrat (Sans-serif)
- **Quotes**: Playfair Display (Serif)

## 🚀 Getting Started

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/KookKookKool/mockup-proj-SONATASANDS-Vacation-Villa.git
   cd mockup-proj-SONATASANDS-Vacation-Villa
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with npx)
   npx serve
   ```

3. **Visit**
   ```
   http://localhost:8000
   ```

### No Build Process Required
This is a static website with no dependencies to install. All libraries are loaded via CDN.

## 📁 Project Structure

```
mockup-proj-SONATASANDS-Vacation-Villa/
│
├── index.html          # Main HTML file (complete website)
└── README.md           # Project documentation
```

## 🎯 Key Features Explained

### GSAP Animations
The website uses several animation techniques:
- **Hero Zoom**: Text scales and fades on scroll
- **Fade Up**: Sections animate into view
- **Slide In**: Villas slide from left/right
- **Stagger**: Multiple items animate in sequence
- **Pop In**: Gallery items scale up with bounce effect

### Responsive Design
- Desktop: Full multi-column layouts
- Tablet/Mobile (< 1024px): Single column, stacked layouts
- Hero text scales down for mobile
- Navigation simplified (can be enhanced with hamburger menu)

### Image Optimization
- Uses Unsplash for high-quality placeholder images
- Lazy loading ready
- Object-fit for consistent aspect ratios

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Customization Guide

### Changing Colors
Edit CSS variables in `:root`:
```css
:root {
    --accent-green: #4F634D;  /* Change to your brand color */
}
```

### Updating Content
- **Property Name**: Search for "SONATA SANDS" in HTML
- **Contact Info**: Update footer section
- **Images**: Replace Unsplash URLs with your own
- **Villa Details**: Edit villa-item sections

### Adding More Villas
Duplicate a `.villa-item` block and update content:
```html
<div class="villa-item">
    <!-- Copy structure from existing villa -->
</div>
```

## 📄 License

This project is open source and available for personal and commercial use.

## 🙏 Credits

- **Images**: [Unsplash](https://unsplash.com/)
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: [Google Fonts](https://fonts.google.com/)
- **Animation**: [GSAP by GreenSock](https://greensock.com/)

## 📧 Contact

For questions or collaboration:
- **Email**: hello@sonatasands.com
- **Phone**: +66 81 234 5678
- **Location**: Krabi, Thailand

---

**Built with ❤️ by NPM Properties**