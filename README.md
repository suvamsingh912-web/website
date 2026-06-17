# ⚡ Flappy Goku - Dragon Ball Z Edition ⚡

A fun, interactive Flappy Bird-style game featuring Goku from Dragon Ball Z, built with HTML5 Canvas and Web Audio API.

## 🎮 Features

- **Animated Goku Character** with Super Saiyan transformations
- **Dragon Ball Z Themed Graphics** with glowing effects
- **Power-Up System** - Collect Ki orbs to power up Kamehameha blasts
- **Ki Blast Mechanic** - Modify pipe gaps with your energy attacks
- **Combo System** - Chain successful passes for bonus multipliers
- **Sound Effects** - Web Audio API for dynamic sound generation
- **Particle Effects** - Smooth animations and visual feedback
- **Responsive Design** - Works on desktop and mobile
- **Local Storage** - Saves your high score and settings

## 🚀 How to Run

### Local Development
```bash
npm install
npm start
```

Then open `http://localhost:8000` in your browser.

### Direct Browser
Open `goku.html` directly in a web browser.

## 🎯 How to Play

- **SPACE or CLICK** - Flap/fly upward
- **Z key or SHIFT+SPACE** - Shoot Ki blasts (costs 20 power)
- **Collect Power Orbs** - Gain Ki energy
- **Avoid Pipes** - Don't hit the obstacles
- **High Score** - Stored in browser

## 🔊 Sound & Music

- **Music Toggle** (🎵 button) - Background music control
- **SFX Toggle** (🔊 button) - Sound effects on/off
- **Volume Slider** - Adjust music volume
- All preferences saved to localStorage

## 📁 File Structure

```
website/
├── goku.html       # Main game file (HTML + CSS + JS)
├── server.js       # Local server for development
├── package.json    # Node.js configuration
├── README.md       # This file
└── .github/        # GitHub Actions workflow for Pages deployment
```

## 🌐 Deployment

This repository includes a GitHub Pages workflow at `.github/workflows/pages.yml`.

### Live site URL
The site should be available at:

`https://suvamsingh912-web.github.io/website`

### Manual publish
If needed, go to GitHub repo Settings → Pages and verify the site is published from the `main` branch.

## 💾 Browser Support

- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Mobile browsers ✅

## 🛠️ Technical Stack

- **HTML5 Canvas** - Game rendering
- **Web Audio API** - Sound generation
- **localStorage** - Data persistence
- **Vanilla JavaScript** - No frameworks

## ✨ Credits

Built with ❤️ using Dragon Ball Z inspiration

## 📝 License

MIT - Feel free to modify and use!