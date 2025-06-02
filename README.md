# Deccan Monogram Website

A modern, responsive website for Deccan Monogram (Multi State Housing Cooperative Society Ltd) built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Interactive gallery with filtering and lightbox
- Notice board with admin panel
- Contact forms with validation
- Google Maps integration
- Channel partner registration system

## Pages

1. Landing Page
   - Introduction
   - History
   - Objectives
   - Administration

2. About Page
   - Board of Directors
   - Society Functions
   - Ledgers and Books
   - Land Provisions
   - Housing Schemes

3. Channel Partner Page
   - Partnership Opportunities
   - Registration Form
   - Requirements
   - Benefits

4. Assistance Page
   - Contact Information
   - Google Maps Location
   - Assistance Request Form

5. Gallery Page
   - Filterable Image Gallery
   - Lightbox View
   - Categories: Residential, Commercial, Amenities, Events

6. Notification Page
   - Admin Login
   - Notice Board
   - Notice Management System

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd deccan-monogram
   ```

2. Configure Google Maps:
   - Replace `YOUR_GOOGLE_MAPS_API_KEY` in `assistance.html` with your actual Google Maps API key
   - Update the coordinates in the `initMap()` function with your society's location

3. Admin Panel Setup:
   - Default credentials (change these in production):
     - Username: admin
     - Password: password
   - Implement proper authentication in production

4. Image Setup:
   - Add your images to the `images` directory
   - Update image paths in HTML files
   - Recommended image sizes:
     - Gallery: 800x600px
     - Hero banner: 1920x1080px
     - Team members: 400x400px

## Development

### File Structure
```
deccan-monogram/
├── index.html
├── about.html
├── channel-partner.html
├── assistance.html
├── gallery.html
├── notification.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/
    ├── hero-bg.jpg
    ├── residential-1.jpg
    ├── residential-2.jpg
    ├── commercial-1.jpg
    ├── commercial-2.jpg
    ├── amenity-1.jpg
    ├── amenity-2.jpg
    ├── event-1.jpg
    └── event-2.jpg
```

### Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome Icons
- Google Maps API
- Lightbox2 for image gallery

## Customization

### Colors
The website uses CSS variables for easy color customization. Edit the following in `style.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --text-color: #333;
    --light-bg: #f5f6fa;
    --white: #ffffff;
}
```

### Content
- Update the contact information in all HTML files
- Replace placeholder text with actual society information
- Add real images to the gallery
- Customize the notice categories in the notification page

## Production Deployment

Before deploying to production:
1. Replace all placeholder content with real content
2. Implement proper backend integration for forms
3. Set up secure authentication for the admin panel
4. Optimize images for web
5. Minify CSS and JavaScript files
6. Update meta tags for SEO
7. Add proper favicon
8. Implement proper error handling
9. Set up analytics

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any queries or support, please contact:
- Email: info@deccanmonogram.com
- Phone: +91 XXXXXXXXXX 