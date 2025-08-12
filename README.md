# Spotter.ai Landing Page

A modern, responsive landing page for Spotter.ai featuring trucking automation solutions. This project includes a sleek inline navigation bar with dropdown menus, replacing the original hamburger menu design.

## Features

- **Modern Navigation**: Inline navigation bar with smooth dropdown menus
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive Dashboard**: 6-module dashboard showcasing Spotter's features
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Performance Optimized**: Efficient code with throttled scroll events
- **Accessibility**: Keyboard navigation and screen reader support

## Technologies Used

- HTML5
- CSS3 (with modern features like backdrop-filter, grid, flexbox)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)
- Vercel for deployment

## Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── vercel.json         # Vercel deployment configuration
└── README.md           # Project documentation
```

## Navigation Features

The navigation bar includes the following sections with dropdown menus:

- **Home** - Direct link to homepage
- **Lens** - Features, Pricing, Request Demo
- **TMS** - Overview, Integrations
- **Sentinel** - How it Works, Pricing
- **Extension** - Direct link to browser extension
- **Spotter App** - Download, Help & Support
- **Loan Calculators** - Direct link
- **Insights** - Blog, News

## Dashboard Modules

1. **US Map Module** - Geographic data visualization
2. **Recruiting Engine** - Spotter CRM with engagement visibility
3. **Load Score** - 65% score with detailed metrics
4. **Visibility Engine** - Spotter TMS with data automation
5. **Safety Automation** - Grade D safety score
6. **Load Board Automation** - Browser extension support

## Deployment

### Deploy to Vercel

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. **Deploy the project**:
   ```bash
   vercel
   ```

3. **Follow the prompts**:
   - Link to existing project or create new
   - Confirm deployment settings
   - Wait for deployment to complete

### Alternative: GitHub Integration

1. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Deploy automatically

## Local Development

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd spotter-ai-landing
   ```

2. **Open in browser**:
   - Simply open `index.html` in your browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # or
     npx serve .
     ```

## Customization

### Colors
The main color scheme uses:
- Primary Teal: `#00d4aa`
- Secondary Red: `#ff6b6b`
- Dark Background: `#0d1117`
- Text Colors: Various shades of white and gray

### Fonts
- Primary: Inter (Google Fonts)
- Fallback: System fonts

### Responsive Breakpoints
- Desktop: 1024px+
- Tablet: 768px - 1023px
- Mobile: < 768px

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

- Optimized images and assets
- Efficient CSS with minimal repaints
- Throttled scroll events for smooth performance
- Lazy loading for better initial page load

## Accessibility

- Semantic HTML structure
- Keyboard navigation support
- ARIA labels where needed
- High contrast color scheme
- Screen reader friendly

## License

This project is created for Spotter.ai. All rights reserved.

## Contact

For questions or support, please contact the development team. 