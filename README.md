# Fiver Pitch

An interactive 5-a-side football pitch application for tactical planning and play visualization.

## Features

### Interactive Pitch
- **Drag & Drop Players**: Move players around the pitch with mouse or touch input
- **Ball Control**: Drag the ball to position it anywhere on the field
- **Realistic Field**: Professional-looking pitch with penalty areas, center circle, and goals
- **Stadium Atmosphere**: Spectator stands on both sides with animated celebrations

### Team Management
- **Kjelsås Team** (Blue): 5 players in 1-2-1 formation
- **Opposition Team** (Red): 5 players in 2-2 formation
- **Goalkeeper Highlighting**: Special yellow/gold styling for goalkeepers

### Tactical Animations
- **Play from Back**: Animated tactical play sequence
  - Choose to play out left or right
  - Watch the build-up play unfold automatically
  - Goalkeeper → Defender → Midfielder progression
- **Automatic Reset**: Players return to starting positions before each play

### Goal Celebrations
- **Score Tracking**: Live score display for both teams
- **Crowd Reactions**: Animated spectator celebrations when goals are scored
- **Team-Specific Colors**: Blue celebration for Kjelsås, red for opposition
- **Auto-Detection**: Automatic goal detection when ball enters goal area

### Responsive Design
- Mobile-friendly touch controls
- Optimized for both desktop and mobile screens
- Smooth animations and transitions

### Progressive Web App (PWA)
- **Installable**: Add to home screen on mobile devices
- **Offline Support**: Works without internet connection
- **App-Like Experience**: Runs in standalone mode without browser UI
- **Custom Icon**: Football pitch themed app icon

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript
- No external dependencies
- Responsive design with flexbox
- Touch and mouse event handling
- CSS animations and gradients

## Getting Started

### Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
npm start
```

### Deploy to Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

Or connect your GitHub repository to Vercel for automatic deployments.

## Usage

1. **Move Players**: Click/tap and drag any player to reposition them
2. **Move Ball**: Click/tap and drag the ball anywhere on the pitch
3. **Score Goals**: Drag the ball into the goal areas (top or bottom)
4. **Run Plays**: Select a direction and click "Spill" to see an animated tactical play
5. **Track Score**: Watch the live score update as goals are scored

### Installing as an App

**On iOS (iPhone/iPad):**
1. Open the site in Safari
2. Tap the Share button
3. Select "Add to Home Screen"
4. Tap "Add"

**On Android:**
1. Open the site in Chrome
2. Tap the menu (three dots)
3. Select "Install app" or "Add to Home Screen"
4. Tap "Install"

**On Desktop (Chrome/Edge):**
1. Look for the install icon in the address bar
2. Click "Install"
3. The app will open in its own window

## Browser Support

Works in all modern browsers with support for:
- CSS Grid & Flexbox
- Touch Events API
- CSS Animations
- ES6 JavaScript

## License

MIT
