# 🎮 Game Boy Photo Booth

A fully functional retro photo booth that captures your photos with an authentic Game Boy aesthetic! Built as a single HTML file for easy deployment anywhere.

![Game Boy Photo Booth](https://img.shields.io/badge/Game%20Boy-Photo%20Booth-green?style=for-the-badge&logo=nintendo-gameboy)

## ✨ Features

### 🎨 Authentic Design
- **Pixel-perfect Game Boy replica** with cream shell and rounded bottom-right corner
- **Classic green LCD screen** with proper proportions and bezel
- **Realistic button layout** with red A/B buttons and black D-pad
- **Speaker grille and Nintendo branding** for complete authenticity

### 📸 Camera Functionality
- **Live camera preview** with real-time Game Boy filter
- **4-color monochrome palette** matching original Game Boy screen
- **Selfie-style mirroring** for natural positioning
- **Flash effect** when taking photos (white screen flash)
- **High-quality photo capture** with retro filtering applied

### 🎮 Interactive Controls
- **START Button**: Activate camera / Return to camera mode
- **A Button**: Capture photo with flash effect
- **B Button**: Download your retro photo
- **Keyboard Support**: Enter (START), Space (A), B key (B)

### 🖥️ Technical Features
- **Single HTML file** - no external dependencies
- **Responsive design** - works on desktop and mobile
- **Cross-browser compatibility** - Chrome, Firefox, Safari, Edge
- **No server required** - runs entirely in the browser
- **Instant deployment** - just open the HTML file

## 🚀 Quick Start

1. **Download** the `gameboy-photo-booth.html` file
2. **Open** it in any modern web browser
3. **Click START** and allow camera access
4. **See yourself** in retro Game Boy green!
5. **Press A** to capture your photo
6. **Press B** to download it

## 🎯 How to Use

### Step 1: Launch
Open `gameboy-photo-booth.html` in your browser. You'll see the classic Game Boy startup screen.

### Step 2: Activate Camera
Click the **START** button. Your browser will request camera permission - click "Allow".

### Step 3: Live Preview
You'll immediately see yourself in the Game Boy screen! After 1 second, the authentic green filter kicks in.

### Step 4: Capture Photo
Press the **A button** (or spacebar) to take your photo. You'll see a camera flash effect!

### Step 5: Download
Press the **B button** to download your retro Game Boy photo with timestamp filename.

## 🔧 Browser Compatibility

- ✅ **Chrome** 53+
- ✅ **Firefox** 36+  
- ✅ **Safari** 11+
- ✅ **Edge** 12+
- ✅ **Mobile browsers** (iOS Safari, Chrome Mobile)

## 📱 Mobile Support

Works great on mobile devices! The responsive design adapts to phone screens while maintaining the authentic Game Boy proportions.

## 🎨 Technical Details

### Game Boy Filter Algorithm
- Converts camera feed to grayscale using luminance formula
- Maps to authentic 4-color Game Boy palette:
  - Darkest Green: `rgb(15, 56, 15)`
  - Dark Green: `rgb(48, 98, 48)`
  - Light Green: `rgb(139, 172, 15)`
  - Lightest Green: `rgb(155, 188, 15)`
- Adds subtle scanlines for authentic CRT effect

### Performance
- **60 FPS** live preview with real-time filtering
- **Hardware acceleration** using Canvas 2D API
- **Optimized rendering** with efficient filter algorithms
- **Minimal memory usage** with proper cleanup

## 🎮 Keyboard Shortcuts

- **Enter**: START button (activate camera)
- **Spacebar**: A button (capture photo)  
- **B**: B button (download photo)

## 🔒 Privacy & Security

- **No data collection** - everything runs locally
- **No server communication** - completely offline
- **Camera access only** - no microphone or other permissions
- **Photos stay local** - only downloaded to your device

## 🌟 Fun Facts

- Built in **single HTML file** (~27KB) with embedded CSS and JavaScript
- **790 lines of code** creating a complete retro experience
- **Pixel-perfect measurements** based on original Game Boy dimensions
- **Authentic color palette** from real Game Boy hardware

## 🎉 Perfect For

- **Retro gaming events** and conventions
- **90s nostalgia** photo booths
- **Social media** content with vintage vibes
- **Web development** portfolio projects
- **Party entertainment** and ice breakers

## 🛠️ Development

Built with vanilla HTML, CSS, and JavaScript - no frameworks needed!

- **HTML5 Canvas** for image processing
- **WebRTC getUserMedia** for camera access
- **CSS Grid & Flexbox** for responsive layout
- **ES6 JavaScript** for modern functionality

## 📄 License

This project is open source and available under the MIT License.

---

*Experience the magic of 90s gaming with modern web technology! 📸🎮*

**Made with ❤️ using Claude Code**