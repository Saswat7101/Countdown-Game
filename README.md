# Countdown Game

A fun and challenging React-based countdown timer game where players test their timing skills across different difficulty levels.

## Description

This project is a web-based game built with React that challenges users to stop a countdown timer as close as possible to a target time. Players can set their name and compete in four difficulty levels, each with increasing target times. The game provides immediate feedback on performance through a result modal.

## Features

- **Player Name Setting**: Enter and display a custom player name
- **Multiple Difficulty Levels**:
  - Easy: 1 second target
  - Not Easy: 5 second target
  - Getting Tough: 10 second target
  - Pros Only: 15 second target
- **Interactive Timer**: Start and stop functionality with real-time countdown
- **Result Feedback**: Modal displaying challenge outcome and time accuracy
- **Responsive Design**: Clean, user-friendly interface

## Technologies Used

- **React 19**: Modern JavaScript library for building user interfaces
- **Vite**: Fast build tool and development server
- **ESLint**: Code linting for maintaining code quality
- **CSS**: Styling for the game interface

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd countdown-game
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in the terminal)

## Usage

1. **Set Your Name**: Enter your name in the input field and click "Set Name"
2. **Choose a Challenge**: Select one of the four difficulty levels
3. **Start the Timer**: Click "Start Challenge" to begin the countdown
4. **Stop at the Right Time**: Try to click "Stop" when you think the target time has elapsed
5. **View Results**: A modal will appear showing your performance

## Scripts

- `npm run dev`: Start the development server
- `npm run build`: Build the project for production
- `npm run lint`: Run ESLint to check code quality
- `npm run preview`: Preview the production build locally

## Project Structure

```
countdown-game/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── Player.jsx
│   │   ├── TimerChallenge.jsx
│   │   └── ResultModal.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is private and for educational purposes.
