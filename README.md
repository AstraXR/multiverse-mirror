# multiverse-mirror

# 🌌 Multiverse Mirror

**A real-time webcam portal that refracts your reflection across three parallel realities.**

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)

---

## 🎭 Overview

The Multiverse Mirror is an experimental web application that transforms your webcam feed in real-time through the aesthetic lens of three distinct parallel universes. Using HTML5 Canvas and vanilla JavaScript, it applies live visual effects at 60fps to create an immersive reality-shifting experience.

This is not augmented reality. This is **alternate reality reflection**.

---

## ✨ The Three Reality Shards

### 🌿 Reality Shard One: The Verdant Spire
Bio-luminescent organic transformation with jade-spectrum light waves, living glass aesthetics, and pulsing bioluminescence effects.

**Visual Effects:**
- Dynamic green wavelength modulation
- Organic glow composite overlays
- Floating bio-particle system
- Harmonic brightness oscillation

### ⚡ Reality Shard Two: Neon Echoes in the Chrome Labyrinth
Cyberpunk data-corruption aesthetic with chromatic aberration, scanline distortion, and neon overlay compositing.

**Visual Effects:**
- RGB channel shifting
- Procedural scanline generation
- Digital noise artifacts
- Dual-tone neon screen compositing (magenta/cyan)
- Temporal glitch effects

### 🌌 Reality Shard Three: The Whispering Void
Cosmic ethereal transformation with nebula gradients, radial distortion fields, and deep-space color grading.

**Visual Effects:**
- Polar coordinate-based swirl distortion
- Radial gradient nebula overlays
- Purple-blue spectrum remapping
- Stellar particle field generation
- Distance-based wave propagation

---

## 🚀 Quick Start

### Option 1: Download and Run Locally

1. Download `multiverse-mirror.html` or clone this repository
2. Double-click the HTML file to open in your browser
3. Grant camera permissions when prompted
4. Select your reality shard using the interface buttons

### Option 2: GitHub Pages (Live Demo)

Visit the live deployment: **[INSERT YOUR GITHUB PAGES URL]**

---

## 💻 Technical Details

### Technologies Used
- **HTML5 Canvas API** - Real-time pixel manipulation
- **MediaDevices API** - Webcam access
- **Vanilla JavaScript (ES6+)** - No frameworks or dependencies
- **CSS3** - Glassmorphism UI effects

### Browser Compatibility
- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

**Note:** Webcam access requires HTTPS or localhost. File protocol (`file://`) works for local testing.

### Performance
- **60 FPS** rendering on modern hardware
- **Real-time** pixel manipulation (no pre-recorded filters)
- **Optimized** Canvas operations for minimal CPU usage
- **Responsive** design (scales to viewport)

---

## 🎨 Features

- **Three Distinct Visual Modes** - Each with unique shader-like effects
- **Real-Time Processing** - Live transformation at 60fps
- **Zero Dependencies** - Pure vanilla JavaScript
- **Privacy-First** - Everything runs locally in-browser
- **Responsive Design** - Works on desktop and tablet
- **Glassmorphism UI** - Modern, semi-transparent controls
- **Dynamic Particle Systems** - Context-aware ambient effects

---

## 🔧 Customization

Want to create your own reality shard? The effect system is modular:

```javascript
// Add a new reality in the renderReality() function
if (currentReality === 3) {
    // Your custom pixel manipulation here
    for (let i = 0; i < data.length; i += 4) {
        data[i] = // Red channel
        data[i + 1] = // Green channel  
        data[i + 2] = // Blue channel
        // data[i + 3] is alpha (usually unchanged)
    }
}
```

---

## 📝 License

MIT License - Feel free to use, modify, and distribute.

---

## 🙏 Credits

**Concept & Development:** ASTRA

**Inspired by:** Quantum mechanics, parallel universe theory, cyberpunk aesthetics, and the question: *"What if every reflection is a glimpse into another timeline?"*

---

## 🌟 Support

If this project resonates with you:
- ⭐ Star this repository
- 🔀 Fork and create your own reality shards
- 💬 Share your experiences and screenshots
- 🎨 Support the creator on [Patreon](INSERT_YOUR_PATREON_LINK)

---

## 🔮 Future Possibilities

- [ ] WebGL shader implementation for more complex effects
- [ ] Reality transition animations
- [ ] Photo/video capture functionality
- [ ] Sound-reactive visual modulation
- [ ] VR/AR integration
- [ ] More reality shards (suggestions welcome!)

---

**"You are not locked into a single timeline. This mirror proves it."**

*Built with curiosity and code by ASTRA* ✨
