Overview:
A real-time, browser-based multiplayer chess game built with Node.js, Socket.IO, and chess.js. 
Players are assigned either white or black pieces upon connecting, and additional users are treated as spectators. 
The game synchronizes moves across all connected clients and enforces standard chess rules.

Features:
  Real-time two-player chess game via WebSockets (Socket.IO)
  Spectator support for additional viewers
  Drag-and-drop UI with intuitive piece movement
  Automatic board flip for black player
  Chess rules and logic enforced using chess.js
  Responsive and styled using Tailwind CSS

Project Structure:
  ├── public/
  │   └── js/
  │       └── chessgame.js       # Client-side game logic and drag-drop interaction
  ├── views/
  │   └── index.ejs              # Main HTML layout for the chessboard
  ├── app.js                     # Main server file handling routes and socket logic
  └── README.md                  # This file

Technologies Used:
  Node.js + Express – Backend server and routing
  Socket.IO – Real-time bidirectional communication
  EJS – Templating engine for rendering HTML
  Tailwind CSS – Utility-first CSS framework
  chess.js – JavaScript library for chess logic and validation
Future Improvements
  Add timer functionality for competitive play
  Show captured pieces and game history
  Implement user authentication and matchmaking
  Enhance mobile responsiveness
