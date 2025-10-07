# Infolore Landing Page Creator

A single-file, client-side landing page generator designed for cold calling campaigns and LinkedIn outreach. Create unlimited personalized landing pages in seconds without any backend infrastructure.

## Features

- Create unlimited landing pages with unique URLs
- Customize headlines, subheadlines, and call-to-action text
- Choose custom color schemes for each page
- Built-in lead capture forms
- Responsive design for mobile and desktop
- No backend required - runs entirely in the browser
- Pages stored in browser localStorage

## Use Cases

- Personalized landing pages for cold call prospects
- Custom pages for LinkedIn outreach campaigns
- Quick demo pages for sales presentations
- A/B testing different messaging
- Event-specific landing pages

## How to Use

### Creating a Landing Page

1. Open the admin panel (default view)
2. Fill out the form:
   - **Page Slug**: URL identifier (e.g., "demo-webinar")
   - **Headline**: Main headline for your page
   - **Subheadline**: Supporting text
   - **CTA Button Text**: Call-to-action button text
   - **Colors**: Choose primary and secondary colors
3. Click "Create Landing Page"
4. Your page is created instantly

### Viewing a Landing Page

1. Click "View" next to any saved page
2. Or share the URL directly: `your-site.com#page-slug`

### Sharing with Prospects

1. Click "Copy URL" next to any page
2. Share the link via email, LinkedIn, or during calls
3. Each prospect gets their personalized page

## Technical Details

### Technology Stack

- Pure HTML, CSS, and JavaScript
- No frameworks or dependencies
- LocalStorage for data persistence
- Hash-based routing for page navigation

### Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

### Data Storage

Pages are stored in the browser's localStorage. Data persists across sessions but is limited to the specific browser and device where pages were created.

### Limitations

- localStorage has a ~5-10MB limit (sufficient for thousands of pages)
- Data is not synced across devices
- Clearing browser data will delete saved pages
- No backend analytics or form submissions (frontend only)

## Future Enhancements

Potential features to add:

- Export pages as JSON backup
- Import previously saved pages
- Analytics integration (Google Analytics, etc.)
- Form submission to external services (Zapier, webhooks)
- More template designs
- Image upload support
- Video embed options

