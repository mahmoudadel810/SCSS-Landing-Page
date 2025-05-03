<!-- @format -->

# Modern Website Template

A clean, responsive website template built with HTML, CSS/SCSS, and JavaScript.

## Preview

![Website Preview](<img width="1433" alt="Screenshot 2025-05-03 at 2 46 17 PM" src="https://github.com/user-attachments/assets/97af82f6-3dcc-48f0-9f4b-6c9674be1aa9" />)



## Features

- Fully responsive design that works on all devices
- Modern UI with smooth animations
- Built with SCSS for better CSS organization
- Lightweight and fast-loading

## Project Structure

```
project/
├── index.html          # Main HTML file
├── styles.scss         # SCSS source file
├── styles.css          # Compiled CSS file
├── styles.css.map      # Source map for debugging
├── images/             # Image directory
│   ├── mac.jpg
│   ├── team1.jpg
│   ├── team2.jpg
│   ├── team3.jpg
│   ├── team4.jpg
│   ├── tech_*.jpg      # Various tech images
├── screenshot.png      # Website preview image
└── README.md           # This file
```

## Getting Started

1. Clone this repository
2. Open `index.html` in your browser to view the site

## Development

### Prerequisites

- Node.js and npm (for SCSS compilation)
- SCSS compiler (like node-sass)

### Compiling SCSS

To compile the SCSS file to CSS:

```bash
# Install node-sass globally if you haven't already
npm install -g node-sass

# Compile SCSS to CSS
node-sass styles.scss styles.css --output-style compressed --source-map true
```

### Watching for Changes

To automatically compile SCSS when files change:

```bash
node-sass --watch styles.scss styles.css --output-style compressed --source-map true
```

## Customization

### Colors

The main colors can be changed in the `styles.scss` file by modifying the variables:

```scss
$primary-color: #f44336;
$secondary-color: #333;
$light-gray: #f1f1f1;
$text-color: #757575;
```

### Layout

The container width and navigation height can be adjusted:

```scss
$container-width: 1200px;
$nav-height: 60px;
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- IE11 (limited support)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Design inspired by W3.CSS templates
- Icons from Font Awesome
- Images from Unsplash
