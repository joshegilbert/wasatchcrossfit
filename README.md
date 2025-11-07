# Wasatch CrossFit Website

A modern, responsive website for Wasatch CrossFit in Layton, Utah.

## Features

- **Fully Responsive**: Mobile-first design that works on all devices
- **Modern Design**: Clean, professional aesthetic with CrossFit energy
- **SEO Optimized**: Meta tags, structured data, and semantic HTML
- **Fast Loading**: Optimized for performance
- **Accessible**: ARIA labels and keyboard navigation support
- **Conversion Focused**: Multiple CTAs for "Book a Free Intro"

## File Structure

```
wasatchcrossfit/
├── index.html                 # Homepage
├── class-schedule.html        # Class schedule page
├── pricing.html               # Pricing page
├── testimonials.html          # Testimonials page
├── book-a-free-intro.html     # Free intro booking page
├── drop-in.html              # Drop-in visitors page
├── location.html              # Location and contact page
├── css/
│   ├── style.css             # Main stylesheet
│   └── responsive.css        # Mobile responsive styles
├── js/
│   └── main.js               # JavaScript functionality
├── images/
│   ├── gallery-1.jpg         # Gallery image 1
│   ├── gallery-2.jpg          # Gallery image 2
│   └── gallery-3.jpg          # Gallery image 3
└── README.md                  # This file
```

## Setup Instructions

1. **Add Images**: Replace placeholder images in the `images/` folder with actual gym photos
   - Recommended sizes: 1200x800px or larger
   - Formats: JPG or WebP
   - Optimize images for web (use tools like TinyPNG or ImageOptim)

2. **Update Google Maps Embed**: 
   - In `location.html`, update the Google Maps iframe src with your actual location embed code
   - Get embed code from: https://www.google.com/maps
   - Search for "825 UT-193, Layton, UT 84041" and click "Share" > "Embed a map"

3. **Verify Form Integration**:
   - PushPress forms are embedded via iframe
   - Form URL: `https://api.grow.pushpress.com/widget/form/uy52Xa6CPygNF6jZcVHU`
   - Verify this URL is correct with Wasatch CrossFit

4. **Test All Links**:
   - Social media links (Facebook, Instagram, YouTube)
   - Phone number links
   - Email links
   - Internal navigation
   - External links (Stripe payment, PushPress forms)

## Customization

### Colors
Edit CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #e63946;    /* Main brand color */
    --secondary-color: #1d3557;   /* Secondary color */
    --accent-color: #f1faee;      /* Accent color */
    --dark-color: #0d1b2a;        /* Dark text */
}
```

### Content
- Update text content directly in HTML files
- All content matches the original Wasatch CrossFit site
- Update contact information if needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized CSS and JavaScript
- Lazy loading for images (if implemented)
- Minimal dependencies
- Fast page load times

## SEO Features

- Semantic HTML5
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Structured data (JSON-LD) for Google
- Canonical URLs
- Alt text for images

## Deployment

1. Upload all files to your web server
2. Ensure proper file permissions
3. Test all pages and forms
4. Submit sitemap to Google Search Console
5. Verify structured data with Google's Rich Results Test

## Maintenance

- Keep images optimized
- Update class schedules as needed
- Update pricing if it changes
- Test forms regularly
- Monitor page load speeds

## Support

For questions or issues, contact:
- Email: carson@wasatchcrossfit.com
- Phone: (801) 771-0784

## License

© 2024 Wasatch CrossFit. All rights reserved.

