# Slide Jantem - Puzzle Game

A web-based puzzle game featuring sliding block mechanics, level creation tools, and pixel art aesthetics with player customization and leaderboard functionality.

![Game Screenshots](im1.png)

## Features

### Core Gameplay
- **Dynamic sliding puzzle mechanics** with grid-based movement
- **20+ challenging levels** across multiple themed environments
- **Real-time puzzle solving** with visual feedback and collision detection
- **Progressive difficulty** system with unlockable content

### Customization & Progression
- **Player avatar customization** with multiple character options
- **Trail effects** and visual customization features
- **Personal score tracking** across all levels
- **Achievement system** and progress monitoring

### Level Creation Tools
- **Manual Level Editor**: Visual interface for creating custom maps
- **Automated Level Generator**: Algorithm-powered level creation with solver verification
- **Workshop System**: Share and discover community-created levels
- **Level Validation**: Built-in puzzle solver ensures all levels are solvable

### Social Features
- **Global Leaderboards** with competitive scoring
- **User Registration** and profile management
- **Score Persistence** across gaming sessions
- **Community Features** for level sharing

## Screenshots

| Main Menu | Gameplay | Level Editor |
|-----------|----------|--------------|
| ![Main Menu](im1.png) | ![Gameplay](im2.png) | ![Manual Editor](im7.png) |

| Customization | Leaderboard | Level Selection |
|---------------|-------------|-----------------|
| ![Customization](im4.png) | ![Leaderboard](im5.png) | ![Auto Editor](im6.png) |

## Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: PHP with session management
- **Database**: MySQL for user data and score tracking
- **Game Engine**: Custom JavaScript implementation
- **Assets**: Pixel art graphics with retro aesthetic

## Installation & Setup

### Prerequisites
- Web server with PHP support (Apache/Nginx recommended)
- MySQL database server
- Modern web browser with JavaScript enabled

### Quick Start
```bash
git clone https://github.com/nolancacheux/SlideJantemGame.git
cd SlideJantemGame

# Set up your web server to serve the project directory
# Configure database connection in bdd/database.php
# Import database schema from provided SQL files
```

### Database Setup
1. Create a MySQL database for the project
2. Update connection settings in `bdd/database.php`
3. Import the database schema and initial data

## Usage

### Game Controls
- **Arrow Keys** or **WASD**: Move your character through the puzzle
- **Mouse**: Navigate menus and interface elements
- **Space**: Interact with game elements

### Level Creation
1. Access the **Manual Creator** from the main menu
2. Use the visual editor to design your puzzle layout
3. Test your level using the built-in validation system
4. Share your creation with the community

## Project Structure

```
├── Milo/              # Main game interface and core gameplay
├── Nolan/             # Level creation tools and workshop features
├── Julien/            # C++ puzzle solver and generation algorithms
├── bdd/               # Database connections and user management
├── code/              # Additional game components
├── css/               # Styling and visual themes
├── js/                # Client-side game logic
├── img/               # Game assets and sprites
└── maps/              # Level data files
```

## Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

### Development Guidelines
- Follow existing code style and conventions
- Test new features thoroughly before submitting
- Update documentation for any new functionality

