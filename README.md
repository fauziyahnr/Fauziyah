# 🎨 Fauziyah - Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and getting in touch with potential clients or employers.

## ✨ Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI** - Clean and professional design with smooth animations
- **Multiple Sections**:
  - Hero/Landing section
  - About Me
  - Featured Projects
  - Skills & Technologies
  - Contact Form
  - Social Media Links
  
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Mobile hamburger menu
  - Animated elements on scroll
  - Form validation
  - Scroll-to-top button

- **Easy to Customize** - Simple structure makes it easy to update content with your own information

## 📁 Project Structure

```
Fauziyah/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # Main stylesheet
│   └── js/
│       └── script.js      # JavaScript functionality
├── README.md              # This file
└── .gitignore            # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML/CSS/JavaScript (for customization)

### Installation

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/fauziyahnr/Fauziyah.git
   cd Fauziyah
   ```

2. **Open in Browser**
   - Simply open `index.html` in your favorite web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js with http-server
     npx http-server
     ```

3. **Visit Local Server**
   - Open your browser and navigate to `http://localhost:8000`

## 🎯 Customization Guide

### 1. Update Your Information

**Edit `index.html`:**
- Replace "Fauziyah" with your name
- Update the "Developer | Designer | Creator" tagline
- Modify the "About Me" section with your bio
- Update social media links (GitHub, LinkedIn, Twitter, etc.)

### 2. Add Your Projects

In the Projects section, update each project card with:
- Project title and description
- Technologies used (update the tags)
- Links to live demo and source code

Example:
```html
<div class="project-card">
    <!-- Project content -->
</div>
```

### 3. Update Skills

Customize the skills section by editing the skill categories:
```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <ul class="skill-list">
        <li>Skill 1</li>
        <li>Skill 2</li>
        <!-- Add more skills -->
    </ul>
</div>
```

### 4. Add Contact Information

Update the contact section with:
- Email address
- Phone number
- Location
- Any other relevant contact details

### 5. Change Colors (Optional)

In `assets/css/style.css`, modify the CSS variables:
```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #ec4899;    /* Accent color */
    --text-dark: #1f2937;
    --bg-light: #f9fafb;
    /* ... other variables */
}
```

### 6. Add a Profile Picture

Replace the placeholder avatar with your actual profile photo:
```html
<!-- Replace this -->
<div class="placeholder-avatar">
    <i class="fas fa-user"></i>
</div>

<!-- With this -->
<img src="path/to/your/image.jpg" alt="Profile Picture" style="width: 300px; height: 300px; border-radius: 15px;">
```

## 🌐 Deployment

### GitHub Pages (Free Hosting)

1. **Create a repository** named `yourusername.github.io`
2. **Push your files** to the repository
3. **Access your site** at `https://yourusername.github.io`

### Steps:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Other Hosting Options
- **Netlify** - Drag and drop deployment
- **Vercel** - Simple deployment from GitHub
- **Firebase Hosting** - Google's hosting solution
- **Traditional Web Hosting** - Any shared or dedicated hosting provider

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript (Vanilla)** - No frameworks, lightweight and fast
- **Font Awesome** - Icon library

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Color Scheme

- **Primary**: #6366f1 (Indigo)
- **Secondary**: #ec4899 (Pink)
- **Text Dark**: #1f2937
- **Background Light**: #f9fafb
- **White**: #ffffff

## 📝 Tips & Best Practices

1. **Keep Content Updated** - Regularly update your projects and skills
2. **Optimize Images** - Use compressed images for faster loading
3. **Mobile First** - Test on mobile devices regularly
4. **SEO Optimization** - Add meta descriptions and keywords
5. **Analytics** - Consider adding Google Analytics to track visitors
6. **Performance** - Use tools like Lighthouse to check performance

## 🔧 Common Issues & Solutions

### Contact Form Not Sending
The current form shows a success message but doesn't send emails. To enable actual email sending:
- Use a backend service like Node.js/Express
- Use services like Formspree, EmailJS, or Netlify Forms
- Update the JavaScript in `assets/js/script.js`

### Images Not Loading
- Ensure image paths are correct
- Check that images are in the correct directory
- Use relative paths: `assets/images/your-image.jpg`

### Mobile Menu Not Working
- Check that JavaScript is enabled
- Verify the hamburger icon is visible on mobile
- Clear browser cache and reload

## 📚 Learning Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)
- [Web.dev](https://web.dev/)

## 📄 License

This project is open source and available under the MIT License. Feel free to use it for personal or commercial projects.

## 🤝 Contributing

If you'd like to improve this portfolio template:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 💬 Support

If you have any questions or need help:
- Check the issues section on GitHub
- Open a new issue with a detailed description
- Contact me via email (update with your email)

## 🌟 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Inspiration from modern portfolio designs

---

**Made with ❤️ by Fauziyah**

Happy coding! 🚀
