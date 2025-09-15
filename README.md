# 🎵 Songify - Web Music Player

**Music for Everyone** - A modern, responsive web-based music player built with HTML, CSS, and JavaScript.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Available-brightgreen)](https://songify-gray.vercel.app/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🚀 Live Demo

**🌐 [View Live Demo](https://songify-gray.vercel.app/)**

Experience Songify in action! The demo showcases all the features including playlist management, audio controls, and responsive design.

## 📸 Screenshots

![Songify Interface](img/cover.jpg)
*Main interface showing the playlist library and music player*

## ✨ Features

### 🎮 Core Functionality
- **Music Playback**: Play, pause, next, and previous track controls
- **Playlist Management**: Multiple categorized playlists with mood-based collections
- **Volume Control**: Adjustable volume with mute/unmute functionality
- **Seek Bar**: Interactive progress bar for track navigation
- **Real-time Updates**: Live track time display and progress tracking

### 🎨 User Interface
- **Responsive Design**: Fully responsive layout that works on desktop and mobile
- **Dark Theme**: Modern dark interface with elegant styling
- **Album Art**: Visual album covers for each playlist
- **Hamburger Menu**: Mobile-friendly navigation with slide-out sidebar
- **Clean Layout**: Spotify-inspired interface design

### 🎵 Music Collections
- **Mood-based Playlists**:
  - Angry (mood)
  - Bright (mood)
  - Chill (mood)
  - Dark (mood)
  - Funky (mood)
  - Love (mood)
  - Uplifting (mood)
- **Artist Collections**:
  - Diljit
  - Karan Aujla
- **Special Collections**:
  - NCS (No Copyright Sounds)
  - Copyright Songs

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Audio**: Web Audio API
- **Styling**: Custom CSS with Flexbox layout
- **Icons**: SVG icons for scalable graphics
- **Data**: JSON-based playlist and song management

## 📁 Project Structure

```
Songify.biz/
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Main stylesheet
│   └── utility.css        # Utility classes
├── js/
│   └── script.js          # Main JavaScript functionality
├── img/                   # SVG icons and images
│   ├── logo.png
│   ├── play.svg
│   ├── pause.svg
│   ├── nextsong.svg
│   ├── prevsong.svg
│   ├── volume.svg
│   ├── mute.svg
│   └── ...
└── songs/                 # Music library
    ├── albums.json        # Album configuration
    ├── Love_(mood)/
    ├── Chill_(mood)/
    ├── Bright_(mood)/
    └── ...
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/songify.git
   cd songify
   ```

2. **Start a local server**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

### Adding Music

1. Create a new folder in the `songs/` directory
2. Add your music files (.mp3 format recommended)
3. Create `info.json` with playlist metadata:
   ```json
   {
       "title": "Your Playlist Name",
       "description": "Your playlist description"
   }
   ```
4. Add `cover.jpg` for album artwork
5. Update `songs/albums.json` to include your new folder

## 🎵 How It Works

### Core Components

1. **Audio Engine**: Built on HTML5 Audio API for seamless playback
2. **Dynamic Loading**: Playlists are loaded dynamically from JSON files
3. **Event-Driven**: User interactions trigger audio control events
4. **State Management**: Current track, playlist, and player state are managed in JavaScript

### Key Functions

- `getSongs(folder)`: Loads songs from a specific playlist folder
- `playMusic(track)`: Handles track playback and UI updates
- `displayAlbums()`: Dynamically creates playlist cards
- `secondsToMinutesSeconds()`: Time formatting utility

## 📱 Responsive Design

Songify is built with mobile-first approach:

- **Mobile**: Hamburger menu with slide-out sidebar
- **Tablet**: Optimized layout for medium screens  
- **Desktop**: Full sidebar with expanded controls

## 🎨 Customization

### Themes
Modify `css/style.css` to customize:
- Color schemes
- Typography
- Layout spacing
- Component styling

### Adding Features
The modular JavaScript structure makes it easy to add:
- Shuffle functionality
- Repeat modes
- Favorites system
- Search functionality

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by Spotify's interface design
- Icons from various open-source collections
- Music samples for demonstration purposes

## 📞 Contact

- **Live Demo**: [https://songify-gray.vercel.app/](https://songify-gray.vercel.app/)
- **Issues**: Please report bugs and feature requests in the Issues section

---

⭐ **Star this repository if you found it helpful!**

*Built with ❤️ for music lovers everywhere*