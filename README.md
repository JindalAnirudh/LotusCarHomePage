# Lotus Car Showcase Website

A stunning, responsive website showcasing Lotus cars with modern design and interactive features. This project recreates the official Lotus Cars website experience with beautiful animations, video backgrounds, and a sleek user interface.

## 🚗 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Video Backgrounds**: Immersive video backgrounds for hero sections
- **Interactive Navigation**: Smooth sliding navigation menu with hamburger toggle
- **Car Models Showcase**: Dedicated sections for different Lotus models (EMEYA, ELETRE, EMIRA, EVIJA)
- **Modern UI/UX**: Clean, modern design with Lotus brand colors and typography
- **Social Media Integration**: Links to social media platforms
- **Grid Layout**: Beautiful grid layout for showcasing different sections
- **Hover Effects**: Smooth hover animations and transitions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with Flexbox, Grid, and animations
- **Font Awesome**: Icons for enhanced visual appeal
- **Video Elements**: HTML5 video for background media

## 📁 Project Structure

```
Car Showcase/
├── index.html              # Main HTML file
├── style.css              # Main stylesheet
├── LOTUS_Roundel_Primary_RGB.png  # Lotus logo favicon
├── images/                # Image assets
│   ├── download.svg       # Lotus logo
│   ├── emeyahome.png     # EMEYA car image
│   ├── Test_drive-Eletre-Desktop.webp  # Test drive image
│   ├── desktop_companycar.jpg  # Company car image
│   ├── webshop-ebike.png # E-bike image
│   ├── webshop-life.png  # Lifestyle shop image
│   ├── tablet_story_comprimised.webp  # Story section image
│   ├── tablet_visit_desktop.jpg  # Visit section image
│   └── [social media icons and other assets]
├── Videos/               # Video assets
│   ├── Home - Headervid - Desktop.mp4  # Main hero video
│   └── PS-Hero_Landing-Desktop.mp4     # Personal showroom video
└── .vscode/             # VS Code settings
    └── settings.json
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for best experience)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/lotus-car-showcase.git
   cd lotus-car-showcase
   ```

2. **Open the website**
   - **Option 1**: Simply open `index.html` in your web browser
   - **Option 2**: Use a local server for better video loading:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have live-server installed)
     live-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **View the website**
   - Open your browser and navigate to `http://localhost:8000` (if using a local server)
   - Or simply double-click `index.html` to open directly in browser

## 🎨 Design Features

### Color Scheme
- **Primary Yellow**: `#FDEF00` (Lotus signature yellow)
- **Black**: `#000000` (Background and text)
- **White**: `#FFFFFF` (Text and accents)

### Key Sections
1. **Hero Section**: Full-screen video background with call-to-action buttons
2. **EMEYA Section**: Showcasing the fully electric Hyper-GT
3. **Personal Showroom**: Interactive experience section
4. **Test Drive Section**: Call-to-action for test drives
5. **Company Benefits**: Fleet and business solutions
6. **Product Grid**: Four-section grid showcasing various Lotus offerings
7. **Footer**: Newsletter signup and comprehensive site links

### Interactive Elements
- Hamburger menu with smooth slide-out navigation
- Hover effects on grid items and buttons
- Video autoplay with loop functionality
- Responsive design breakpoints

## 📱 Responsive Design

The website is fully responsive with breakpoints for:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## 🔧 Customization

### Changing Colors
Edit the CSS variables or direct color values in `style.css`:
```css
/* Primary brand color */
background-color: #FDEF00;

/* Text colors */
color: white;
color: black;
```

### Adding New Sections
1. Add HTML structure in `index.html`
2. Style the new section in `style.css`
3. Ensure responsive behavior is maintained

### Updating Content
- Replace images in the `images/` folder
- Update video files in the `Videos/` folder
- Modify text content directly in `index.html`

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This project is for educational and portfolio purposes. Lotus Cars and all related trademarks are property of their respective owners.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact

Your Name - your.email@example.com

Project Link: [https://github.com/yourusername/lotus-car-showcase](https://github.com/yourusername/lotus-car-showcase)

## 🙏 Acknowledgments

- [Lotus Cars](https://www.lotuscars.com/) for design inspiration
- [Font Awesome](https://fontawesome.com/) for icons
- Video content used for demonstration purposes

---

**Note**: This is a showcase project and is not affiliated with Lotus Cars Ltd. All trademarks and copyrights belong to their respective owners.
