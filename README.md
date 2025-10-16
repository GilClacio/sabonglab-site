# sabongLAB Mobile Apps Showcase

A professional website showcasing essential mobile applications developed by sabongLAB for Sabungeros and cockfighting enthusiasts. Built with modern web technologies and optimized for GitHub Pages deployment.

## 🚀 Live Website

Visit the live website at: [sabonglab.com](https://sabonglab.com)

## 🎯 Mission

sabongLAB is your go-to platform for essential cockfighting tools, dedicated to developing innovative mobile applications specifically designed for Sabungeros. We empower the cockfighting community with comprehensive digital tools that enhance every aspect of the sabong experience.

## 📋 Features

- **Essential App Portfolio**: Showcase of mobile applications developed specifically for Sabungeros
- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **App Downloads**: Links and information for downloading essential sabong tools
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Mobile First**: Designed with mobile users in mind
- **Interactive Elements**: Smooth scrolling, mobile navigation, and form handling
- **GitHub Pages Ready**: Configured for easy deployment on GitHub Pages

## 📱 Essential Mobile Apps for Sabungeros

### 🎮 Sabong Arena
Interactive mobile game featuring traditional cockfighting simulation with modern gaming mechanics and multiplayer support for Sabungeros.

### 📊 Sabong Stats  
Comprehensive statistics and analysis app for Sabungeros to track performance, breeding records, and fighting trends.

### 🏆 Tournament Tracker
Essential tool to organize and manage sabong tournaments with real-time scoring, bracket management, and live updates.

### 📱 Sabong Community
Social networking app connecting Sabungeros worldwide with forums, chat, event listings, and knowledge sharing.

### 📚 Breeding Guide
Educational app with comprehensive guides, tips, and best practices specifically for cockfighting breeding and training.

### ⏰ Event Scheduler
Never miss a sabong event with our scheduling app featuring notifications, reminders, and calendar integration for cockfighting events.

## 🛠 Technologies Used

- **HTML5**: Semantic markup with accessibility in mind
- **CSS3**: Modern styling with Flexbox and Grid layouts
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Google Fonts**: Inter font family for modern typography
- **GitHub Pages**: Static site hosting

## 📁 Project Structure

```
sabonglab-site/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── CNAME              # Custom domain configuration
└── README.md          # Project documentation
```

## 🎯 Website Purpose

This website serves as the primary showcase for essential mobile applications developed by sabongLAB specifically for Sabungeros, featuring:

- **Essential Tool Portfolio**: Display of all essential sabong apps with descriptions and features
- **Download Access**: Easy access to app downloads on various platforms
- **Tool Features**: Highlighting key features and capabilities for Sabungeros
- **Community Support**: Support and contact details for the sabong community
- **Update Notifications**: Newsletter signup for essential app updates and new tool releases

## 🎯 Target Audience

- **Sabungeros**: Cockfighting enthusiasts and participants
- **Breeders**: Individuals involved in gamecock breeding
- **Tournament Organizers**: Event managers and coordinators
- **Sabong Community**: The broader cockfighting community worldwide

## 🚀 Deployment Instructions

### Setting up GitHub Pages

1. **Push to GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: SabongLab website"
   git branch -M main
   git remote add origin https://github.com/GilClacio/sabonglab-site.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

3. **Configure Custom Domain**
   - In the same Pages settings, under "Custom domain"
   - Enter: `sabonglab.com`
   - Check "Enforce HTTPS" (recommended)

### DNS Configuration

Configure your domain DNS settings:

1. **For Apex Domain (sabonglab.com)**
   - Create A records pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`

2. **For WWW Subdomain (optional)**
   - Create a CNAME record: `www.sabonglab.com` → `gilclacio.github.io`

3. **Verification**
   - Wait for DNS propagation (can take up to 24 hours)
   - GitHub will automatically verify your domain

## 🔧 Local Development

### Prerequisites
- A modern web browser
- A local web server (optional, for development)

### Running Locally

1. **Simple Method** (for viewing only)
   - Open `index.html` directly in your browser

2. **With Live Server** (recommended for development)
   ```bash
   # If you have Node.js installed
   npx live-server
   
   # Or if you have Python installed
   python -m http.server 8000
   
   # Or if you have PHP installed
   php -S localhost:8000
   ```

3. **Using VS Code Live Server Extension**
   - Install "Live Server" extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

## 📝 Customization Guide

### Updating Content

1. **App Information**
   - Add new essential sabong apps in the apps section of `index.html`
   - Update app descriptions, features tailored for Sabungeros
   - Modify download links and platform availability
   - Update app statistics in the about section

2. **Download Links**
   - Update Google Play Store and App Store links for essential apps
   - Add direct APK download links for sabong tools
   - Update system requirements for optimal performance

3. **Styling**
   - Colors: Update CSS custom properties in `styles.css`
   - Fonts: Change font imports and font-family declarations
   - Layout: Modify grid and flexbox properties for better tool showcase

4. **Images**
   - Add app screenshots and icons for sabong tools to the project folder
   - Update image references in HTML and CSS
   - Optimize images for web (WebP format recommended)

### Adding New Sections

1. Create new HTML section in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Update navigation menu if needed
4. Add smooth scrolling functionality in `script.js`

## 🎨 Design System

### Colors
- Primary: `#667eea` (Blue gradient start)
- Secondary: `#764ba2` (Purple gradient end)
- Background: `#f8fafc` (Light gray)
- Text: `#333` (Dark gray)
- Accent: `#666` (Medium gray)

### Typography
- Font Family: Inter (Google Fonts)
- Headings: 600-700 weight
- Body: 400 weight
- Line Height: 1.6 for readability

### Spacing
- Container max-width: 1200px
- Section padding: 80px vertical
- Grid gaps: 2-4rem
- Border radius: 8-16px for modern look

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and up
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🔍 SEO Features

- Semantic HTML5 structure
- Meta description and keywords
- Open Graph tags (add as needed)
- Proper heading hierarchy (H1-H6)
- Alt text for images (add when images are included)
- Schema markup (can be added for enhanced SEO)

## 🚀 Performance Optimizations

- Minified CSS and JavaScript (can be added in build process)
- Optimized Google Fonts loading
- Efficient CSS Grid and Flexbox layouts
- Lazy loading for images (implement when adding images)
- Critical CSS inlining (can be added for better performance)

## 🔒 Security Considerations

- HTTPS enforcement through GitHub Pages
- No sensitive data in client-side code
- Form validation on both client and server side
- Content Security Policy (can be added via headers)

## 📊 Analytics Setup (Optional)

To add Google Analytics:

1. Create a Google Analytics account
2. Add tracking code to `index.html` before closing `</head>` tag:
   ```html
   <!-- Google Analytics -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
   <script>
     window.dataLayer = window.dataLayer || [];
     function gtag(){dataLayer.push(arguments);}
     gtag('js', new Date());
     gtag('config', 'GA_TRACKING_ID');
   </script>
   ```

## 🐛 Troubleshooting

### Common Issues

1. **Site not loading on custom domain**
   - Check DNS settings
   - Verify CNAME file contains correct domain
   - Wait for DNS propagation (up to 24 hours)

2. **Images not displaying**
   - Check file paths are correct
   - Ensure images are in the repository
   - Verify image file extensions

3. **Mobile menu not working**
   - Check JavaScript console for errors
   - Verify script.js is properly linked
   - Test on different devices/browsers

4. **Styles not applying**
   - Clear browser cache
   - Check CSS file path in HTML
   - Validate CSS syntax

## 📞 Support

For technical support or questions about our essential sabong apps:
- Email: apps@sabonglab.com
- Support: support@sabonglab.com
- GitHub Issues: [Create an issue](https://github.com/GilClacio/sabonglab-site/issues)

## 📄 License

This project is licensed under the MIT License - see the repository for details.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

**sabongLAB** - Essential Mobile Apps for Sabungeros
Built with ❤️ for the Sabungero community worldwide