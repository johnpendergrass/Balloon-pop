# TSBalloonie - Complete HTML5 Balloon Popping Game

🎈 **Ready to Play!** 🎈

**Just open `TSBalloonie.html` in any modern web browser - that's it!**

No installation, no setup, no server required. All HTML, CSS, and JavaScript are contained in the single `TSBalloonie.html` file.

---

## Overview

TSBalloonie is a complete, polished HTML5 balloon popping game with a delightful Toy Story theme. Originally started as "Balloon-pop" on August 18, 2025, it was renamed to TSBalloonie on August 19, 2025 to better reflect its whimsical Toy Story theming.

The entire game was developed using Claude Code (Anthropic's AI coding assistant) and represents a fully-featured browser-based game with professional-quality gameplay mechanics, animations, and sound.

---

## Quick Start

1. **Download or clone this repository**
2. **Open `TSBalloonie.html` in your web browser** 
3. **Start playing immediately!**

Alternative files to run:
- `index.html` (if present) 
- `TSBalloonie.html` ← **Main game file**

**That's it!** Everything needed is contained in the single HTML file.

***** NOTE: these assets files are also used in the game:

   --BG-1.png, BG-2.png, BG-3.png, BG-4.png, BG-5.png
   --TSBalloonie-background.png
   --TSBalloonie-logo.png
   --Buzz-01.mp3, Buzz-02.mp3, Buzz-03.mp3
   --Fanfare-01.mp3

I think the game will run without these assets present, but have not tested it.

### 🎯 Advanced Start Options

**Start at Any Level**: Add `?level=X` to the URL to start at a specific level (1-10)
```
TSBalloonie.html?level=5        # Start at level 5
TSBalloonie.html?level=8        # Start at level 8
```

**Debug Mode**: Add `?level=X&score=Y` for testing with custom starting scores
```
TSBalloonie.html?level=5&score=1000000     # Level 5 with 1 million points
TSBalloonie.html?level=8&score=50000000    # Level 8 with 50 million points
```

---

## Game Features

### Core Gameplay
- **10 Progressive Levels** - Increasing difficulty with more balloons and challenges
- **Three Skill Levels**: Rex (Easy), Woody (Medium), Buzz (Hard) with different speeds and time limits
- **Physics-Based Movement** - Realistic balloon floating and collision detection
- **Precise Custom Cursor** - Triangle-tip accuracy for perfect targeting
- **Dynamic Backgrounds** - 5 Toy Story themed backgrounds that change during gameplay

### Scoring System
- **Base Points**: 50 points per balloon
- **Streak Bonuses**: 5+ consecutive hits trigger multiplier bonuses
- **Sequence Bonuses**: Pop numbered balloons in order (1, 2, 3...) for massive points
- **Rolling Odometer Display** - Smooth animated score counter
- **Persistent Leaderboard** - Top 5 scores saved locally

### Audio Experience
- **Victory Fanfare** - Triumphant sound when completing all 10 levels
- **Gameplay Sounds** - 3 different Buzz Lightyear sound effects
- **Smart Preloading** - All audio preloaded for perfect timing
- **Sound Toggle** - Visual toggle (sounds always play - it's a joke!)

### User Interface
- **Game Summary Box** - Real-time statistics in upper-right corner
- **Skill Level Selection** - Color-coded buttons with Toy Story character themes
- **Top 5 Leaderboard** - Persistent high scores with localStorage
- **Custom Cursor** - Shows current streak count
- **Amiga-Style ABOUT Dialog** - Humorous credits with foreign character authenticity

### Victory Celebration
- **Spinning Logo Animation** - TSBalloonie logo spins majestically when you win
- **Perfect Positioning** - Logo centers beautifully on screen
- **Victory Fanfare** - Triumphant music plays during the celebration
- **Smooth Animations** - Professional-quality CSS transforms

### Special Features
- **ALT-P Cheat Code** - Secret functionality with "CHEATER!" detection
- **Complete Game State Persistence** - Resume where you left off
- **Comprehensive Debug Tools** - 15+ console functions for development
- **Responsive Design** - Works on desktop and mobile browsers

---

## Technical Details

### Architecture
- **Single File Design** - Everything in `TSBalloonie.html` (~3,400 lines)
- **No Dependencies** - Pure HTML5, CSS3, and vanilla JavaScript
- **No Build Process** - Ready to run directly in browser
- **Modern Web Standards** - ES6+, Canvas API, LocalStorage, Audio API

### Performance
- **60fps Gameplay** - Transform-only CSS animations for smooth performance
- **Efficient Collision Detection** - Optimized algorithms for real-time gameplay  
- **Memory Management** - Proper cleanup and garbage collection friendly
- **Audio Optimization** - Smart preloading prevents audio delays
- **Minimal DOM Manipulation** - Performance optimized during gameplay

### Browser Compatibility
- **Modern Browsers** - Chrome, Firefox, Safari, Edge (recent versions)
- **Mobile Support** - Responsive design works on tablets and phones
- **UTF-8 Support** - Proper foreign character rendering in ABOUT dialog
- **Audio Support** - Modern browser audio APIs

---

## File Structure

```
tsballoonie/
├── TSBalloonie.html              # Main game file (EVERYTHING IS HERE!)
├── index.html                    # Alternative entry point (if present)
├── README.md                     # This file
├── TSBalloonie-logo.png         # Game logo (1024x1024)
├── BG-1.png through BG-5.png   # Background images
├── Buzz-01.mp3                  # Gameplay sound effect 1
├── Buzz-02.mp3                  # Gameplay sound effect 2  
├── Buzz-03.mp3                  # Gameplay sound effect 3
├── Fanfare-01.mp3               # Victory celebration fanfare
├── TSBalloonie.html.backup      # Complete working backup
└── Claude-ToBeContinued-*.txt   # Development documentation
```

**Important**: All HTML, CSS, and JavaScript code is contained within `TSBalloonie.html`. The external files are only assets (images and sounds).

---

## How to Play

### Getting Started
1. **Choose Your Skill Level**: Rex (Easy), Woody (Medium), or Buzz (Hard)
2. **Click "Launch Level 1"** to begin
3. **Pop balloons** by clicking on them with your custom cursor

### Gameplay Tips
- **Watch for numbered balloons** - Pop them in sequence (1, 2, 3...) for bonus points
- **Maintain streaks** - 5+ consecutive hits without missing triggers multipliers
- **Time management** - Each level has a time limit based on your skill level
- **Aim carefully** - The custom cursor shows exactly where you'll hit

### Advanced Strategies
- **Sequence Priority** - Always prioritize numbered balloons for massive points
- **Streak Building** - Focus on consistent hits rather than rushed clicking
- **Time Planning** - Scan for numbered balloons at the start of each level
- **Cheat Code** - Press ALT-P if you're stuck (but you'll be marked as a cheater!)

### Victory Condition
Complete all 10 levels to trigger the epic victory celebration with spinning logo and fanfare!

---

## Development History

### Original Concept (August 18-19, 2025)
- Started as simple "Balloon-pop" game
- Renamed to "TSBalloonie" for Toy Story theming
- Basic balloon popping with simple scoring

### Evolution to Complete Game
The project grew from a basic balloon popper into a full-featured game through iterative development:

#### Core Systems Added
- Multi-level progression (10 levels)
- Skill level system (Rex/Woody/Buzz)
- Advanced scoring (streaks, sequences, bonuses)
- Dynamic difficulty scaling
- Persistent leaderboards

#### Polish & Professional Features
- Victory celebration animations
- Audio system with victory fanfare
- Custom cursor system
- Professional UI components  
- Comprehensive game state management

#### Final Touches
- Logo positioning perfection
- Victory fanfare implementation  
- Enhanced ABOUT dialog with foreign character authenticity
- Complete backup and documentation system

### Development Methodology
- **AI-Assisted Development** - Built entirely with Claude Code
- **Iterative Enhancement** - Continuous improvement through user feedback
- **Plan-First Approach** - Each feature planned before implementation
- **Comprehensive Testing** - All systems tested across browsers
- **Performance Optimization** - 60fps target maintained throughout

---

## Version History

- **v0.02**: Original working version with basic odometer
- **v0.03-v0.05**: Core gameplay and UI development  
- **v0.06-v0.10**: Advanced features and polish
- **v0.11-v0.18**: Final enhancements, logo positioning, fanfare
- **v0.19.1**: Current version - completely finished (August 22, 2025)

---

## Technical Implementation Notes

### Audio System
- 4 total audio files (3 gameplay + 1 victory fanfare)
- Preloading system prevents audio delays
- Fallback audio creation if preloading fails
- Volume optimization (0.7 for gameplay, 0.8 for fanfare)

### Animation System  
- CSS transform-only animations for optimal performance
- Victory logo positioning uses viewport units (vh) for responsiveness
- Smooth keyframe animations with cubic-bezier easing

### Scoring Algorithm
- Base balloon points: 50 per balloon
- Streak multipliers: Calculated based on consecutive hits
- Sequence bonuses: Exponential rewards for numbered balloon sequences
- Real-time odometer updates with smooth digit rolling

### Game State Management
- LocalStorage persistence for leaderboards
- Complete game state tracking
- Proper cleanup between levels and games
- Resume functionality for interrupted sessions

---

## Deployment

### Local Testing
```bash
# Simple HTTP server (recommended)
python3 -m http.server 8000

# Then open: http://localhost:8000/TSBalloonie.html
```

### Production Deployment
1. Upload `TSBalloonie.html` and asset files to web server
2. Ensure MIME types are configured for .mp3 and .png files
3. No server-side processing required
4. Works with any static hosting (GitHub Pages, Netlify, etc.)

### Distribution Package
For complete portability, include these files:
- `TSBalloonie.html` (required)
- All `.png` image files (required for visuals)
- All `.mp3` audio files (required for sound)
- Optional: `README.md` for documentation

---

## Browser Requirements

### Minimum Requirements
- **Modern Browser**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **JavaScript**: ES6+ support required
- **Audio**: Web Audio API support
- **Canvas**: HTML5 Canvas API support
- **Storage**: LocalStorage for persistent leaderboards

### Recommended
- **Desktop Browser** for optimal experience
- **Speakers/Headphones** for full audio experience
- **Mouse** for precise balloon popping (touchscreen works but less precise)

---

## Troubleshooting

### Game Won't Load
- Ensure JavaScript is enabled
- Check browser console for errors
- Verify all asset files are in same directory
- Try a different modern browser

### No Sound
- Check browser audio permissions
- Verify .mp3 files are present and accessible
- Some browsers require user interaction before playing audio
- Click the sound toggle once (it's mostly decorative!)

### Performance Issues
- Close other browser tabs
- Disable browser extensions temporarily
- Ensure hardware acceleration is enabled
- Try a different browser

### Mobile Issues
- Use landscape orientation for best experience
- Ensure touch targets are accessible
- Some mobile browsers may have audio limitations

---

## License

MIT License - Free to use, modify, and distribute.

Feel free to use this as a learning resource or starting point for your own games!

---

## Credits

**Game Development**: Claude Code (Anthropic AI Assistant)
**Project Design**: John (Seattle, WA)  
**Assets**: Created by ChatGPT-4
**Inspiration**: Toy Story universe (with apologies to Disney)

**Special Thanks**: To anyone who enjoys popping balloons and the whimsical world of Toy Story!

---

## Fun Facts

- The ABOUT dialog contains intentionally humorous foreign character "misspellings" to simulate an incompetent programmer
- The sound toggle is mostly a visual joke - sounds always play!
- There are 15+ debug console commands hidden in the code
- The victory fanfare was the final feature added to complete the game
- The entire project contains over 3,400 lines of code in a single HTML file
- ALT-P cheat code will mark you as a "CHEATER!" but still works

**Enjoy the game! 🎈✨**