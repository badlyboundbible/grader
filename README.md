# Assessment Calculator

A modern, mobile-first assessment calculator with a beautiful interface designed for smartphones. Complete 10 questions with Yes/Neutral/No answers, add an overall assessment modifier, and get your final grade from A+ to U-.

## Features

- ❤️ **Beautiful Mobile Design** - Optimized for smartphones and tablets
- 📱 **Progressive Web App** - Install directly to your home screen
- 🎯 **Smart Scoring System** - Yes (+1), Neutral (0), No (-1) with grade modifiers
- 🌈 **Color-Coded Questions** - Three distinct sections with visual grouping
- ⚡ **Real-time Progress** - Track completion with animated progress bar
- 🎨 **Modern UI** - Card-based selections with smooth animations

## Live Demo

Visit the deployed app: `[Your GitHub Pages URL will go here]`

## Installation as Web App

### iPhone/iPad:
1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add" to confirm

### Android:
1. Open the app in Chrome
2. Tap the menu (three dots)
3. Tap "Add to Home screen"
4. Tap "Add" to confirm

## Question Categories

- **Questions 1-3 (K, P, A)** - Pink section
- **Questions 4-6 (P, E, C)** - Cyan section  
- **Questions 7-10 (M, K, I, C)** - Yellow section
- **Final Assessment** - Overall modifier (Positive +, Neutral, Negative -)

## Grading System

| Score | Grade | With Modifier |
|-------|-------|---------------|
| 10    | A     | A+, A, A-     |
| 9     | B     | B+, B, B-     |
| 8     | C     | C+, C, C-     |
| ...   | ...   | ...           |
| -10   | U     | U+, U, U-     |

## Development

### Local Setup
1. Clone this repository
2. Open `index.html` in your browser
3. No build process needed - runs directly in browser

### GitHub Pages Deployment
1. Push files to your GitHub repository
2. Go to Settings > Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/" (root) folder
5. Your app will be available at `https://yourusername.github.io/repository-name`

## Files Structure

```
assessment-calculator/
├── index.html          # Main app file
├── manifest.json       # PWA manifest
├── sw.js              # Service worker for offline functionality
├── icon-192x192.png   # App icon (192x192)
├── icon-512x512.png   # App icon (512x512)
└── README.md          # This file
```

## Technologies Used

- **React** - UI framework
- **Tailwind CSS** - Styling
- **PWA** - Progressive Web App capabilities
- **Service Worker** - Offline functionality

## Browser Support

- ✅ Chrome (Android & Desktop)
- ✅ Safari (iOS & macOS)
- ✅ Firefox
- ✅ Edge

## License

MIT License - feel free to use and modify as needed.

---

Made with ❤️ for modern mobile experiences