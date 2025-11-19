# Musical Advent Calendar 🎄🎵

A React-based interactive Advent Calendar that unlocks a curated Spotify song for every day of December. The application features a "Midnight Christmas" aesthetic with glassmorphism effects, snow animations, and persistent unlock logic.

✨ Features

Interactive Calendar Grid: 25 unlockable days with custom animations.

Spotify Integration: Embedded music player for each day's song.

Smart Locking Logic: Days are locked based on the current date.

Time Travel Debugger: built-in developer tool to simulate different dates (useful for testing animations and logic before December).

Responsive Design: Fully responsive layout optimized for mobile and desktop.

Atmospheric Effects: CSS-based snow falling animation and glassmorphism UI.

🛠️ Tech Stack

Framework: React 18

Styling: Tailwind CSS

Icons: Lucide React

Build Tool: Vite

🚀 Getting Started

Prerequisites

Node.js (v16 or higher)

npm or yarn

Installation

Clone the repository

git clone [https://github.com/yourusername/musical-advent-calendar.git](https://github.com/yourusername/musical-advent-calendar.git)
cd musical-advent-calendar


Install dependencies

npm install


Run the development server

npm run dev


Build for production

npm run build


📂 Project Structure

├── src/
│   ├── App.jsx        # Main application logic and components
│   ├── main.jsx       # Entry point
│   └── index.css      # Tailwind directives
├── public/
├── package.json
├── tailwind.config.js
└── vite.config.js


🎨 Customization

To change the songs, edit the ADVENT_DATA array in src/App.jsx. Each entry requires a valid Spotify Track ID.

const ADVENT_DATA = [
  { day: 1, id: 'SPOTIFY_TRACK_ID', title: "Song Title", artist: "Artist Name" },
  // ...
];


📄 License

MIT
