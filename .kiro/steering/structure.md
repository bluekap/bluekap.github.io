# Project Structure

## Root Files
- `index.html` - Main portfolio page (customized for Vaibhav Goswami)
- `demo.html` - Original CEEVEE template demo (reference/backup)
- `readme.txt` - Original template documentation and licensing
- `favicon.png` - Site favicon
- `debug.log` - Development/error logging

## Directory Organization

### `/css/` - Stylesheets
- `default.css` - Base styles and reset
- `layout.css` - Main layout and component styles
- `media-queries.css` - Responsive breakpoints
- `fonts.css` - Font declarations
- `magnific-popup.css` - Lightbox plugin styles
- `/font-awesome/` - Font Awesome icon font files
- `/fontello/` - Custom icon font files
- `/fonts/` - Web font files

### `/js/` - JavaScript Files
- `init.js` - Main initialization and custom scripts
- `jquery-1.10.2.min.js` - jQuery library
- `jquery-migrate-1.2.1.min.js` - jQuery migration helper
- `jquery.fittext.js` - Responsive text plugin
- `jquery.flexslider.js` - Slider functionality
- `magnific-popup.js` - Lightbox plugin
- `modernizr.js` - Feature detection
- `waypoints.js` - Scroll-triggered animations

### `/images/` - Media Assets
- `profilepic.jpg` - Current profile photo
- `profilepic_old.jpg`, `profilepic_orig.jpg` - Previous versions
- `header-background.jpg` - Hero section background
- `loader.gif` - Loading animation
- `overlay-bg.png`, `overlay-zoom.png` - UI overlays
- `tf.jpg`, `ust_1.png`, `ust_2.png` - Company/project logos
- `/portfolio/` - Portfolio project images

### `/inc/` - Server-side Includes
- `sendEmail.php` - Contact form processing script

### `/resume/` - Documents
- `Resume.pdf` - Downloadable resume file

## File Naming Conventions
- Use lowercase with hyphens for CSS/JS files
- Use camelCase for JavaScript variables and functions
- Use descriptive names for image files
- Keep file names web-safe (no spaces, special characters)

## Code Organization
- CSS follows component-based organization
- JavaScript uses jQuery patterns with namespace protection
- PHP follows basic procedural structure for simple functionality
- HTML uses semantic markup with proper sectioning

## Asset Management
- Images optimized for web delivery
- CSS and JS files are separate (no bundling)
- External CDN resources for major libraries (Tailwind, Font Awesome)
- Local fallbacks for critical dependencies