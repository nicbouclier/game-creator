# Sonic Adventure on the Megadrive

A momentum-based platformer inspired by classic Sonic games, designed for TV remote controls and optimized for Comcast X1/Xumo TV.

## Game Overview

**Theme**: Sonic Adventure adapted for Sega Megadrive capabilities  
**Controls**: TV Remote D-pad + Enter only  
**Canvas**: 1280×720 with 32px safe margins  
**Style**: Authentic 16-bit Megadrive aesthetic  

## How to Play

- **LEFT/RIGHT Arrows**: Move and build momentum (Walk → Run → Dash)
- **UP Arrow**: Jump (height increases with speed)
- **DOWN Arrow**: Spin Dash (hold to charge, release for speed burst)
- **ENTER**: Brake/precision control

## Objective

Navigate through 6 platform levels collecting golden rings. Use momentum and strategic movement to reach higher platforms. Collect all 10 rings and reach the orange goal ring to complete the game.

## Technical Specifications

- **JavaScript**: 204 lines (under 300 limit)
- **Total Size**: ~11KB (under 3MB limit)
- **Rendering**: 2D Canvas only
- **Dependencies**: None (single file)
- **Performance**: 60fps gameplay

## File Structure

```
games/sonic-mega/
├── index.html          # Complete game (HTML + CSS + JS)
├── manifest.json       # Asset and palette specifications
└── README.md          # This documentation
```

## Compliance

✅ **Platform**: 1280×720 canvas with proper safe margins  
✅ **Controls**: TV remote D-pad + Enter only  
✅ **Visual**: 16-bit color palette and TV-readable fonts  
✅ **Code**: Under 300 lines JavaScript  
✅ **Assets**: Under 3MB total size  
✅ **Rendering**: 2D Canvas only (no WebGL)  

## Gameplay Features

- **Momentum Physics**: 3 speed states with realistic acceleration
- **Speed-Based Jumping**: Jump height scales with movement speed
- **Spin Dash Mechanic**: Charge and release for burst speed
- **Ring Collection**: 10 rings with progressive difficulty
- **Camera System**: Smooth following with proper boundaries
- **Visual Feedback**: Speed-based color changes and effects

## Future Enhancements

- Replace rectangle sprites with detailed pixel art
- Add chiptune audio effects and background music
- Implement additional levels and power-ups
- Add more detailed sprite animations

---

*Created for Comcast X1/Xumo TV platform compliance*