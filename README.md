# Breakout Rogue

A roguelike/roguelite twist on the classic Breakout arcade game, featuring procedural generation, power-ups, and persistent upgrades.

## Features

### Core Gameplay
- Classic breakout mechanics with smooth paddle and ball physics
- Destructible bricks with satisfying particle effects
- Responsive controls (Arrow keys or A/D)

### Roguelike Elements

#### Power-ups
- **Multiball** - Split balls into multiple projectiles
- **Wide Paddle** - Temporarily expand paddle width
- **Slow Motion** - Reduce ball speed
- **Pierce** - Ball passes through bricks
- **Magnetism** - Attract ball to paddle
- **Extra Life** - Add an additional life
- **Coins** - Instant coin bonus
- **Explosive** - Ball causes area damage
- **Sticky Paddle** - Ball sticks to paddle on contact

#### Brick Types
- **Normal** (Red) - 1 hit to destroy
- **Tough** (Cyan) - 2 hits to destroy
- **Armored** (Green) - 3 hits to destroy
- **Golden** - High coin rewards
- **Explosive** - Causes area damage when destroyed
- **Mystery** - Random rewards and surprises

#### Progression System
- **Persistent Upgrades** - Purchase permanent improvements with coins
- **Level Scaling** - Difficulty increases with each level
- **Combo System** - Chain brick destructions for score multipliers
- **Roguelite Mode** - Continue with upgrades after game over

### Upgrades Shop
- Swift Paddle - Increase movement speed
- Speed Control - Better ball speed management
- Extra Life - Start with additional lives
- Coin Magnet - Increase coin drop rates
- Combo Master - Enhanced combo multipliers
- Power Extender - Longer power-up durations

## How to Play

1. Open `index.html` in a web browser
2. Click "START GAME" to begin
3. Use Arrow keys or A/D to move the paddle
4. Press SPACE to release the ball
5. Destroy all bricks to advance levels
6. Collect power-ups and coins
7. Purchase upgrades between games

## Controls

- **Left/Right Arrow** or **A/D** - Move paddle
- **Space** - Release ball from paddle

## Game Modes

- **Restart** - Start fresh with no upgrades
- **Continue** - Keep your upgrades and coins (roguelite mode)

## Technical Details

Built with vanilla JavaScript and HTML5 Canvas, featuring:
- Smooth 60 FPS gameplay
- Particle effects system
- Dynamic lighting and glow effects
- Responsive collision detection
- Procedural level generation

## License

MIT