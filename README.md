# 🎙️ PodcastHub: Modern Podcast Platform

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/euii-ii/podcasthub) 
[![License](https://img.shields.io/badge/license-MIT-blue)](./LICENSE) 
[![Version](https://img.shields.io/badge/version-2.0.0-orange)](https://github.com/euii-ii/podcasthub/releases)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A modern, responsive podcast platform built with vanilla web technologies. Perfect for podcast creators, listeners, and developers learning web development.

---

## 🌟 Overview

**PodcastHub** is a feature-rich, responsive website designed to provide an exceptional podcast listening experience. This platform combines modern web design principles with intuitive functionality, making it easy for users to discover, browse, and enjoy podcast content across all devices.

Whether you're a podcast creator looking to showcase your content or a developer seeking to understand modern web development practices, this project serves as an excellent foundation and learning resource.

---

## ✨ Key Features

### 🏠 **Dynamic Homepage**
- Eye-catching hero section with featured episodes
- Latest episodes showcase with automatic updates
- Podcast statistics and subscriber metrics
- Newsletter signup integration

### 📺 **Episode Management**
- Comprehensive episode library with search and filtering
- Detailed episode pages with show notes and timestamps
- Episode categories and tagging system
- RSS feed integration for automatic updates

### 🎵 **Advanced Media Player**
- Custom-built HTML5 audio player with modern UI
- Play, pause, skip forward/backward (15s intervals)
- Progress bar with click-to-seek functionality
- Volume control with mute option
- Playback speed adjustment (0.5x to 2x)
- Keyboard shortcuts for accessibility

### 📱 **Responsive Design**
- Mobile-first approach with progressive enhancement
- Optimized for all screen sizes (320px to 4K)
- Touch-friendly interface for mobile devices
- Accessible design following WCAG guidelines

### 🎨 **Modern UI/UX**
- Clean, minimalist design with dark/light theme toggle
- Smooth animations and micro-interactions
- Loading states and skeleton screens
- Progressive Web App (PWA) capabilities

---

## 🖼️ Screenshots

| Desktop View | Mobile View |
|--------------|-------------|
| ![Desktop Screenshot](assets/images/screenshots/desktop-view.png) | ![Mobile Screenshot](assets/images/screenshots/mobile-view.png) |

---

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Text editor (VS Code recommended)
- Basic understanding of HTML, CSS, and JavaScript (for customization)

### Installation

```bash
# Clone the repository
git clone https://github.com/euii-ii/podcasthub.git

# Navigate to project directory
cd podcasthub

# Optional: Install development dependencies (if using build tools)
npm install

# Start local development server
npm run dev
# OR simply open index.html in your browser
```

### Development Server Options

```bash
# Using Python 3
python -m http.server 8080

# Using Node.js http-server
npx http-server -p 8080

# Using PHP (if available)
php -S localhost:8080

# Then visit: http://localhost:8080
```

---

## 📁 Project Structure

```
podcasthub/
│
├── 📄 index.html              # Main landing page
├── 📄 episodes.html           # Episode listing page
├── 📄 episode-detail.html     # Individual episode page
├── 📄 about.html             # About page
│
├── 🎨 assets/
│   ├── css/
│   │   ├── main.css          # Main stylesheet
│   │   ├── components.css    # Component-specific styles
│   │   ├── responsive.css    # Media queries
│   │   └── themes.css        # Light/dark theme styles
│   │
│   ├── js/
│   │   ├── app.js           # Main application logic
│   │   ├── player.js        # Audio player functionality
│   │   ├── episodes.js      # Episode management
│   │   └── utils.js         # Utility functions
│   │
│   ├── images/
│   │   ├── logos/           # Brand logos and icons
│   │   ├── episodes/        # Episode artwork
│   │   ├── screenshots/     # Documentation images
│   │   └── backgrounds/     # Background images
│   │
│   └── audio/
│       └── episodes/        # Audio files
│           ├── episode-001.mp3
│           ├── episode-002.mp3
│           └── ...
│
├── 📋 docs/
│   ├── API.md              # API documentation
│   ├── CONTRIBUTING.md     # Contribution guidelines
│   └── DEPLOYMENT.md       # Deployment instructions
│
├── 🧪 tests/
│   ├── unit/               # Unit tests
│   └── integration/        # Integration tests
│
├── 📦 package.json         # Project dependencies
├── 📜 LICENSE              # MIT License
├── 🔧 .gitignore          # Git ignore rules
└── 📋 README.md           # Project documentation
```

---

## 🛠️ Technology Stack

| Category | Technology | Purpose | Version |
|----------|------------|---------|---------|
| **Frontend** | HTML5 | Structure & Semantics | Latest |
| | CSS3 | Styling & Animations | Latest |
| | JavaScript (ES6+) | Interactivity & Logic | Latest |
| **Design** | CSS Grid | Layout System | Latest |
| | Flexbox | Component Layout | Latest |
| | CSS Variables | Theme Management | Latest |
| **Media** | HTML5 Audio API | Audio Playback | Latest |
| | Web Audio API | Advanced Audio Features | Latest |
| **Performance** | Intersection Observer | Lazy Loading | Latest |
| | Service Workers | Offline Functionality | Latest |

---

## 🎯 Usage Guide

### Basic Navigation
- **Browse Episodes**: Navigate to the episodes page to view all available content
- **Play Episodes**: Click any episode to start playback with the integrated player
- **Search**: Use the search bar to find specific episodes or topics
- **Filter**: Apply filters by category, date, or duration

### Media Player Controls

| Control | Action | Keyboard Shortcut |
|---------|--------|-------------------|
| Play/Pause | Toggle playback | `Space` |
| Skip Forward | Jump 15 seconds ahead | `→` |
| Skip Backward | Jump 15 seconds back | `←` |
| Volume Up | Increase volume | `↑` |
| Volume Down | Decrease volume | `↓` |
| Mute/Unmute | Toggle audio | `M` |
| Speed Control | Change playback speed | `S` |

### Accessibility Features
- Full keyboard navigation support
- Screen reader compatibility
- High contrast mode available
- Focus indicators for all interactive elements

---

## 🎨 Customization

### Theming
The website supports custom theming through CSS variables:

```css
:root {
  /* Primary Colors */
  --primary-color: #6366f1;
  --primary-dark: #4f46e5;
  --primary-light: #a5b4fc;
  
  /* Background Colors */
  --bg-primary: #ffffff;
  --bg-secondary: #f8fafc;
  --bg-accent: #f1f5f9;
  
  /* Text Colors */
  --text-primary: #1e293b;
  --text-secondary: #64748b;
  --text-accent: #94a3b8;
  
  /* Player Settings */
  --player-height: 80px;
  --player-border-radius: 12px;
}
```

### Adding New Episodes
1. Add audio files to `assets/audio/episodes/`
2. Add episode artwork to `assets/images/episodes/`
3. Update the episodes data in `assets/js/episodes.js`:

```javascript
const episodes = [
  {
    id: 'episode-001',
    title: 'Your Episode Title',
    description: 'Episode description...',
    audioUrl: 'assets/audio/episodes/episode-001.mp3',
    imageUrl: 'assets/images/episodes/episode-001.jpg',
    duration: '45:30',
    publishDate: '2025-06-01',
    category: 'Technology'
  }
];
```

---

## 🚀 Deployment

### Static Hosting (Recommended)
Deploy to any static hosting service:

```bash
# Netlify
npm run build
netlify deploy --prod --dir=dist

# Vercel
vercel --prod

# GitHub Pages
# Push to gh-pages branch
git subtree push --prefix dist origin gh-pages
```

### Docker Deployment
```dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

---

## 🧪 Testing

### Running Tests
```bash
# Install test dependencies
npm install --dev

# Run unit tests
npm run test:unit

# Run integration tests
npm run test:integration

# Run all tests with coverage
npm run test:coverage
```

### Browser Testing
The project is tested across:
- ✅ Chrome 90+ (Desktop & Mobile)
- ✅ Firefox 88+ (Desktop & Mobile)
- ✅ Safari 14+ (Desktop & Mobile)
- ✅ Edge 90+ (Desktop)
- ✅ Samsung Internet 14+

---

## 🤝 Contributing

We welcome contributions from the community! Please read our [Contributing Guide](./docs/CONTRIBUTING.md) before getting started.

### Development Workflow
1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Make** your changes with proper testing
4. **Commit** with conventional commits (`git commit -m 'feat: add amazing feature'`)
5. **Push** to your branch (`git push origin feature/amazing-feature`)
6. **Create** a Pull Request

### Code Style Guidelines
- Use consistent indentation (2 spaces)
- Follow semantic HTML practices
- Use modern CSS features (Grid, Flexbox, Custom Properties)
- Write clean, commented JavaScript
- Ensure mobile-first responsive design

---

## 📊 Performance Metrics

| Metric | Score | Status |
|--------|-------|--------|
| Performance | 95/100 | ✅ Excellent |
| Accessibility | 98/100 | ✅ Excellent |
| Best Practices | 100/100 | ✅ Perfect |
| SEO | 92/100 | ✅ Excellent |

*Scores based on Lighthouse audit*

---

## 🔄 Changelog

### Version 2.0.0 (Latest)
- ✨ Added dark/light theme toggle
- 🎵 Enhanced media player with advanced controls
- 📱 Improved mobile responsiveness
- ⚡ Performance optimizations
- 🔍 Added search and filtering functionality

### Version 1.5.0
- 🎨 UI/UX improvements
- 🔧 Bug fixes and stability improvements
- 📈 Added analytics integration

[View Full Changelog](./CHANGELOG.md)

---

## 🐛 Known Issues & Roadmap

### Current Limitations
- [ ] Safari iOS autoplay restrictions
- [ ] Limited offline functionality
- [ ] No user authentication system

### Upcoming Features
- [ ] User accounts and playlists
- [ ] Social sharing integration
- [ ] Advanced analytics dashboard
- [ ] Multi-language support
- [ ] Podcast RSS feed generator
- [ ] Comment system for episodes
- [ ] Mobile app version

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](./LICENSE) file for details.

```
MIT License

Copyright (c) 2025 PodcastHub

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🙏 Acknowledgments

- **HTML5 Audio API** for robust audio playback capabilities
- **CSS Grid & Flexbox** for modern layout systems
- **Unsplash** for high-quality stock images
- **Font Awesome** for beautiful icons
- **Open Source Community** for inspiration and best practices

---

## 📞 Support & Contact

**Project Maintainer**: [Your Name](https://github.com/euii-ii)

### Get Help
- 📧 **Email**: podcast-support@example.com
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/euii-ii/podcasthub/issues)
- 💬 **Feature Requests**: [GitHub Discussions](https://github.com/euii-ii/podcasthub/discussions)
- 📚 **Documentation**: [Project Wiki](https://github.com/euii-ii/podcasthub/wiki)

### Demo & Links
- 🌐 **Live Demo**: [podcasthub-demo.netlify.app](https://podcasthub-demo.netlify.app)
- 📖 **Documentation**: [docs.podcasthub.com](https://docs.podcasthub.com)
- 🎨 **Design System**: [design.podcasthub.com](https://design.podcasthub.com)

---

## ⭐ Show Your Support

If this project helped you or you found it interesting:

- ⭐ **Star** the repository
- 🍴 **Fork** it for your own projects
- 📢 **Share** it with fellow developers
- 🐛 **Report** bugs to help improve it
- 💡 **Suggest** new features
- ✍️ **Write** a blog post about your experience

---

## 📈 Project Stats

![GitHub stars](https://img.shields.io/github/stars/euii-ii/podcasthub?style=social)
![GitHub forks](https://img.shields.io/github/forks/euii-ii/podcasthub?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/euii-ii/podcasthub?style=social)

---

*Built with ❤️ for the podcasting community and web development enthusiasts*

**Happy Podcasting! 🎙️✨**
