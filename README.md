# Pinpoint App Landing Page

This repository contains the landing page for the Pinpoint app, a location tracking application that automatically detects and records user trips.

## Overview

The Pinpoint landing page is a lightweight, responsive website built with:
- HTML5
- Tailwind CSS (loaded via CDN)
- Minimal vanilla JavaScript

The website is designed to be fast-loading, mobile-friendly, and easily maintainable.

## Structure

```
/
├── index.html           # Main landing page
├── assets/              # Static assets directory
│   ├── logo.svg         # Pinpoint logo
│   ├── logo-white.svg   # White version of logo for dark backgrounds
│   ├── favicon.ico      # Website favicon
│   ├── hero-screenshot.png  # Hero section main image
│   └── screenshot*.png  # App screenshots for carousel
└── README.md            # This file
```

## Development

To work on this site locally:

1. Clone this repository
2. Open `index.html` in your browser
3. Make changes to the HTML, CSS, or JavaScript as needed
4. Refresh your browser to see changes

Since the site uses Tailwind CSS via CDN, no build step is required for development.

## Screenshots

The website uses screenshot images to showcase the app's features. Replace the placeholder images in the `/assets` directory with actual screenshots of the application:

- `hero-screenshot.png` - Main hero section image (app's main screen)
- `screenshot1.png` - Trip History screen
- `screenshot2.png` - Trip Details screen
- `screenshot3.png` - Location Details screen
- `screenshot4.png` - Profile/Statistics screen

## Deployment

This website is designed to be deployed to any static web hosting service:

1. GitHub Pages: Commit and push your changes to the `main` branch
2. Amazon S3: Upload the files to an S3 bucket configured for static website hosting
3. Netlify/Vercel: Connect your repository for automatic deployment

## Shared Links Functionality

This website also serves as a link target for trips shared from the Pinpoint app. The shared link functionality is handled by the app-related code in the repository.

## Customization

### Colors

The primary colors used throughout the site are:
- Primary blue: `#1E90FF`
- Dark blue: `#0066CC`
- Light blue: `#87CEFA`

To change these colors, modify the Tailwind configuration in the `<head>` section of `index.html`.

### Content

Update the text content in `index.html` to change the marketing messages, feature descriptions, and other content.

### Images

Replace the placeholder images in the `assets` directory with actual screenshots and images of your app.

## License

All rights reserved. © 2025 Pinpoint
