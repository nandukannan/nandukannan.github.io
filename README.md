# Nandu Kannan Portfolio

A modern, responsive portfolio website for Nandu Kannan, a Data Analyst.

## Features

- Fully responsive design that works on all devices
- Interactive navigation menu that highlights the current section
- Smooth scrolling to sections
- Timeline layout for work experience
- Skills categorization with hover effects
- Modern contact form (frontend only)
- Animated elements on scroll
- Social media links

## Technologies Used

- HTML5
- CSS3 with modern features (Flexbox, CSS Variables, etc.)
- JavaScript (ES6+)
- Font Awesome for icons
- Google Fonts (Poppins)

## Project Structure

```
/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── script.js       # JavaScript functionality
└── images/             # Folder for images (add your own)
```

## How to Use

1. Clone or download this repository
2. Open `index.html` in your browser to view the portfolio
3. Customize the content in `index.html` to add your own information
4. Modify styles in `css/styles.css` to match your personal branding
5. Add your own profile picture to the `images` folder (and update the HTML accordingly)

## Customization

### Colors

The color scheme can be easily changed by modifying the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #4361ee;
    --secondary-color: #3a0ca3;
    /* Other colors... */
}
```

### Fonts

The portfolio uses Google Fonts (Poppins). You can change it by:

1. Adding a different font link in the `<head>` of `index.html`
2. Updating the font-family in the CSS variables

### Adding Projects

You can add a projects section by creating a new section in the HTML with a similar structure to the existing sections.

### Adding a Real Form Backend

The contact form is currently for demonstration only. To make it functional:

1. Set up a backend service (PHP, Node.js, etc.) to handle form submissions
2. Update the form action attribute in the HTML
3. Modify the JavaScript form handling in `script.js`

## License

Feel free to use this template for your personal portfolio.

## Credits

- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts](https://fonts.google.com/) 