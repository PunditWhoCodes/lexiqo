# 🧠 Lexiqo Project
The Lexiqo is a Next.js application that challenges players to guess a word within a limited number of attempts. The game features multiple difficulty levels, each with its unique word list and point system. Players can track their progress, unlock new levels, and compete with others to achieve the highest score.

## 🚀 Features
- **Multiple Difficulty Levels**: Each level has a unique set of words and point systems, providing a challenging and engaging experience for players.
- **Word Guessing Mechanism**: Players can guess letters, and the game will provide feedback in the form of colored tiles, indicating correct or incorrect guesses.
- **Progress Tracking**: Players can track their progress, including the number of wins, losses, and points earned.
- **Unlock New Levels**: As players progress through the game, they can unlock new levels with increasingly difficult words.
- **Competitive Leaderboard**: Players can compete with others to achieve the highest score and rank on the leaderboard.

## 🛠️ Tech Stack
- **Frontend**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS, PostCSS
- **State Management**: React Hooks
- **Audio Management**: Web Audio API
- **Storage**: LocalStorage
- **Utilities**: clsx, tailwind-merge

## 📦 Installation
To get started with the project, follow these steps:
1. Clone the repository: `git clone https://github.com/your-repo/word-guessing-game.git`
2. Install dependencies: `npm install` or `yarn install`
3. Start the development server: `npm run dev` or `yarn dev`

## 💻 Usage
1. Open the application in your web browser: `http://localhost:3000`
2. Select a difficulty level and start playing
3. Guess letters to fill in the word
4. Track your progress and unlock new levels

## 📂 Project Structure
```markdown
components
├── GameBoard.tsx
├── GameStats.tsx
├── LevelSelector.tsx
├── GameTimer.tsx
lib
├── audioManager.ts
├── gameLogic.ts
├── utils.ts
hooks
├── useLocalStorage.ts
pages
├── index.tsx
public
├── index.html
styles
├── globals.css
tsconfig.json
next.config.js
postcss.config.js
tailwind.config.ts
package.json
README.md
```

## 📸 Screenshots


## 🤝 Contributing
We welcome contributions to the Word Guessing Game project. If you're interested in contributing, please fork the repository and submit a pull request with your changes.

## 📝 License
The Word Guessing Game is licensed under the MIT License.

## 📬 Contact
For questions or feedback, please contact us at [nawalrai.chetan@gmail.com](mailto:nawalrai.chetan@gmail.com).
