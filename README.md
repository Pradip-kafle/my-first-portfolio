# BIT Student Portfolio

A modern, responsive portfolio website designed for BIT (Bachelor of Information Technology) students.

## Features

- **Modern Design**: Clean and professional layout with smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, skill bar animations, and form validation
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: Typing effect, parallax scrolling, and hover effects

## Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Education Section**: Academic background and current studies
4. **Skills Section**: Technical skills with animated progress bars
5. **Contact Section**: Contact information and contact form

## Customization

### Personal Information
Update the following in `index.html`:

- **Name**: Change "Hello, I'm a BIT Student" in the hero section
- **Phone Number**: Update the phone number in the contact section
- **Education Details**: Modify the education information
- **Skills**: Adjust skill levels and add/remove skills as needed

### Styling
Modify `style.css` to change:
- Colors (primary color is currently #2563eb)
- Fonts (currently using Poppins)
- Layout and spacing
- Animations and transitions

### Functionality
Edit `index.js` to:
- Modify form handling
- Change animation speeds
- Add new interactive features
- Customize notifications

## How to Use

1. **Open the website**: Simply open `index.html` in a web browser
2. **Navigate**: Use the navigation menu or scroll through sections
3. **Contact**: Fill out the contact form to send messages
4. **Mobile**: The site is fully responsive and works on all devices

## File Structure

```
portfolio/
├── index.html      # Main HTML structure
├── style.css       # All styling and responsive design
├── index.js        # JavaScript functionality
└── README.md       # This file
```

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Customization Tips

### Adding Your Photo
Replace the placeholder icon in the hero section with your actual photo:
```html
<div class="profile-placeholder">
    <img src="your-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### Adding More Skills
Add new skill cards in the skills section:
```html
<div class="skill-card">
    <div class="skill-icon">
        <i class="fas fa-code"></i>
    </div>
    <h4>Your Skill</h4>
    <div class="skill-level">
        <div class="skill-bar" data-level="85"></div>
    </div>
</div>
```

### Changing Colors
Update the primary color in `style.css`:
```css
:root {
    --primary-color: #your-color-here;
}
```

## Contact Information

Your current contact details are displayed in the contact section:
- Phone: +977 9765953884
- Education: BIT Student at Lumbini Adarsha Degree College
- Location: Nepal

## Future Enhancements

Consider adding:
- Project portfolio section
- Blog section
- Downloadable resume
- Social media links
- Dark mode toggle
- Multi-language support

## License

This portfolio template is free to use and modify for personal and educational purposes.

---

**Note**: This portfolio is specifically designed for a BIT student with knowledge of C++ and Java, studying at Lumbini Adarsha Degree College. Customize the content to match your specific background and skills. # my-first-portfolio
