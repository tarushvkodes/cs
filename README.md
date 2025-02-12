# CS Resources Website

A comprehensive collection of Computer Science learning resources, featuring a modern, responsive design with animated cards and sections.

## 🌟 Features

- Responsive layout that adapts to all screen sizes
- Animated elements using AOS (Animate On Scroll) library
- Clean and modern card-based design
- Sticky navigation header
- Hero section with background image
- Google Analytics integration
- Organized sections for different resource types:
  - Online Courses
  - Interactive Tutorials
  - Books & Documentation
  - Coding Practice
  - Competitive Programming
  - Tools & Communities
  - Specialized & Research

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- AOS Animation Library
- Google Analytics

## 📦 Dependencies

- AOS (Animate On Scroll) v2.3.1
- Google Analytics tracking script

## 🎨 Design Features

### Layout
- Responsive grid system using CSS Grid
- Fluid typography and spacing
- Card-based content organization
- Sticky navigation header (on desktop)

### Animations
- Fade and zoom effects on cards
- Fade animations on section headers
- Smooth scroll behavior
- Hover effects on cards and buttons

### Colors
- Primary: #0077cc (Blue)
- Background: #f4f4f4 (Light Gray)
- Text: #333 (Dark Gray)
- White: #fff
- Card shadows: rgba(0,0,0,0.1)

## 📱 Responsive Breakpoints

- Mobile: Up to 768px
  - Stack navigation items
  - Adjust hero section height
  - Remove sticky header

## 🚀 Getting Started

1. Clone the repository
2. Replace the Google Analytics ID (`G-JPF8S8WX8N`) with your own
3. Update the banner image path in the CSS (`banner.png`)
4. Modify the content in each section as needed
5. Deploy to your preferred hosting platform

## 📝 Customization

### Adding New Cards
```html
<div class="card" data-aos="zoom-in">
    <h3>Title</h3>
    <p>Description</p>
    <a href="URL" target="_blank" class="button">Visit Site</a>
</div>
```

### Modifying Animations
```javascript
AOS.init({
    duration: 1000,
    easing: 'ease-in-out',
    once: true
});
```

## 📄 License

© 2025 Tarushv Kosgi. All rights reserved.

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Contact

For questions or feedback, please reach out to Tarushv Kosgi.
