# Project Ah'Kan - Coming Soon Page

A responsive "Coming Soon" landing page for Project Ah'Kan, an NGO focused on ocean conservation.

## Features

- Responsive design that works on mobile, tablet, and desktop devices
- Countdown timer to launch date
- Newsletter subscription form
- Animated background with subtle ocean-themed particle effects
- Social media links
- Modern, clean design that aligns with the ocean conservation theme

## Files

- `index.html` - The main HTML structure
- `styles.css` - CSS styling with responsive breakpoints
- `script.js` - JavaScript for countdown timer, form handling, and animations
- `images/` - Directory containing background and logo images
- `fonts/` - Directory containing custom fonts

## Usage

Simply open the `index.html` file in a web browser to view the coming soon page. For production, upload all files to your web hosting provider.

## Customization

### Changing the Launch Date

The countdown timer is set to 3 months from the current date by default. To change this:

1. Open `script.js`
2. Find the `updateCountdown()` function
3. Modify the `launchDate` variable to your desired launch date

### Custom Colors

The color scheme can be modified in the `styles.css` file by changing the CSS variables in the `:root` selector:

```css
:root {
  --primary-color: #0057b7; /* Ocean blue */
  --accent-color: #ffffff;
  --text-color: #ffffff;
  --dark-blue: #003a7a;
  --light-blue: #4c99e6;
}
```

### Newsletter Form

The newsletter form currently displays a success message when submitted but does not actually store the email addresses. To connect it to a backend:

1. Modify the form submission code in `script.js`
2. Add your API endpoint or server-side code to process the form data

## Browser Compatibility

This landing page is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

All rights reserved. © 2024 Project Ah'Kan.
