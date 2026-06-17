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
# Install dependencies (Node.js required)
npm install

# Start the server
npm start
```

Server runs at `http://localhost:8000`

### Using HTTP Server (Python)
```bash
python -m http.server 8000
```

### Direct Browser
Simply open `goku.html` in a web browser

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
flappy-goku/
├── goku.html       # Main game file (HTML + CSS + JS)
├── server.js       # Local server for development
├── package.json    # Node.js configuration
└── README.md       # This file
```

## 🌐 Deployment Options

### GitHub Pages (Recommended)
1. Push to GitHub repository
2. Go to Settings → Pages
3. Select main branch as source
4. Game will be live at `https://yourusername.github.io/flappy-goku`

### Vercel / Netlify
1. Connect your GitHub repository
2. Deploy automatically
3. Live URL provided

### Traditional Hosting
- Upload `goku.html` to any web hosting service
- Access via your domain

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

## 📊 Game Mechanics

- **Score System** - Points for passing pipes
- **Combo Multiplier** - Chains of successful passes
- **Difficulty Scaling** - Game gets harder over time
- **Collision Detection** - Precise hit detection
- **Particle System** - Visual effects for actions

## ✨ Credits

Built with ❤️ using Dragon Ball Z inspiration

## 📝 License

MIT - Feel free to modify and use!