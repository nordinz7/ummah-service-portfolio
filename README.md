# Ummah Service - Free Development Support

A static website offering free web development and software engineering services for Islamic organizations, mosques, and community projects.

## 🌟 About

Ummah Service is a personal initiative to give back to the Muslim community by offering professional development services at no cost. This website serves as a portfolio and contact point for Islamic organizations seeking technical support.

## 🚀 Services Offered

- **Web Development**: Modern, responsive websites with Islamic-friendly design
- **Mobile Applications**: Custom apps for Islamic education and community engagement
- **Backend Systems**: Database design, APIs, and content management systems
- **Technical Consulting**: Architecture planning and technology guidance

## 📱 Features

- Fully responsive design
- Islamic-themed color palette and styling
- Contact form with validation
- Mobile-friendly navigation
- Performance optimized
- SEO friendly
- Accessible design

## 🛠️ Technologies Used

- HTML5
- CSS3 (Modern features like CSS Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (ES6+)
- Font Awesome icons
- Google Fonts (Inter)
- GitHub Pages deployment

## 📦 Deployment

This site is designed to be deployed on GitHub Pages. To deploy:

1. Fork or clone this repository
2. Update the `_config.yml` file with your details:
   - Change `url` to your GitHub Pages URL
   - Update `baseurl` to your repository name
   - Replace contact information with your own
3. Update contact information in `index.html`
4. Enable GitHub Pages in your repository settings
5. Your site will be available at `https://yourusername.github.io/repository-name`

## 🎨 Customization

### Colors
The site uses CSS custom properties for easy color customization. Update the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #2c5530;    /* Main green */
    --primary-light: #4a7c59;    /* Light green */
    --primary-dark: #1a3d1f;     /* Dark green */
    --secondary-color: #d4a574;  /* Gold accent */
    --accent-color: #8b4513;     /* Brown accent */
}
```

### Content
- Edit `index.html` to update services, about section, and contact information
- Modify the hero section text to reflect your specific offerings
- Update the technology stack in the about section
- Replace placeholder email addresses with your actual contact information

### Styling
- All styles are in `styles.css` with organized sections
- Mobile-responsive design with breakpoints at 768px and 480px
- Islamic geometric patterns implemented with CSS

## 📧 Contact Integration

The contact form includes client-side validation and provides user feedback. For full functionality, you'll need to integrate with a form handling service such as:

- Formspree
- Netlify Forms
- EmailJS
- Custom backend solution

To integrate with Formspree (recommended for GitHub Pages):

1. Sign up at [formspree.io](https://formspree.io)
2. Update the form action in `index.html`:
```html
<form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## 🔧 Development

To run locally:

1. Clone the repository
2. Open `index.html` in your browser
3. For development with live reload, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using VS Code Live Server extension
   ```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤲 Islamic Values

This project is created with the intention of serving the Muslim community as a form of sadaqah jariyah (continuous charity). All services offered through this platform are provided free of charge to Islamic organizations and community projects.

May Allah accept this effort and make it beneficial for the ummah. Ameen.

## 🌐 Browser Support

- Chrome/Edge (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Mobile browsers

## ✨ Contributing

While this is a personal service website, suggestions and improvements are welcome. Please feel free to open issues or submit pull requests.

---

**Bismillah** - In the name of Allah, the Most Gracious, the Most Merciful.