**Real-Time Multiplayer Ping Pong Game (Frontend)**

This repository contains the React frontend implementation of a real-time multiplayer ping pong game. The backend (Python with WebSocket support) is not included in this version.

**Folder Structure**
/frontend
 └── /src
     └── /game
         ├── game.js      // Main game logic (React component)
         └── game.css     // Styles for the game


**Features**

Real-Time Gameplay: Basic game mechanics implemented using React and the DOM API.
Obstacles: Dynamic obstacles placed randomly on the board.
Scoring System: Player scores are tracked and displayed.
Keyboard Controls:
Player 1: W (Up), S (Down)
Player 2: Arrow Up, Arrow Down

**How to run**

1. Clone the repository:

git clone <repository_url>
cd frontend

2. Install dependencies:

npm install
Start the development server:

3. Start
npm start
Open your browser and go to http://localhost:3000.

**Future Work**

Backend: Implement a Python backend with WebSocket support for real-time multiplayer synchronization.
WebSocket Communication: Enable real-time updates between multiple clients.
Enhanced UI/UX: Add better graphics, sound effects, and animations.
Error Handling: Improve error handling for edge cases.

**Known Issues**
The current version does not support multiplayer over the network.

Author:
Sandeep Kisku
