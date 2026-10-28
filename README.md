# Tic Tac Toe

An interactive, elegant Tic Tac Toe game built with **React**, **TypeScript**, and **Vite**. Play against an AI opponent powered by **Gemini**, or with a friend in local two-player mode â€” complete with sound effects, move history, and customizable board options.

## Features

- ðŸ§  **Single-player AI mode** â€” challenged by a Gemini-powered opponent
- ðŸ‘¥ **Local two-player mode** â€” play on the same device
- ðŸ”Š **Sound effects** â€” audio feedback for moves and results
- ðŸ•˜ **Move history** â€” review and step through the game
- âš™ï¸ **Customizable board** â€” adjust options to your liking
- ðŸŽ¨ **Modern UI** â€” built with Tailwind CSS and smooth animations

## Tech stack

| Layer | Tools |
| --- | --- |
| Frontend | React 19, TypeScript, Vite |
| Styling | Tailwind CSS, Lucide icons, Motion |
| Backend | Express, tsx |
| AI | Google GenAI (Gemini) |

## Getting started

### Prerequisites

- Node.js 18+
- A Gemini API key

### Setup

```bash
# 1. Clone the repository
git clone https://github.com/akarapuswapanth98-netizen/tic-tac-toe.git
cd tic-tac-toe

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env
# then edit .env and add your Gemini API key

# 4. Start the dev server
npm run dev
```

The app runs on the port defined in `vite.config.ts` (default `http://localhost:3000`).

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build |
| `npm run lint` | Type-check with `tsc --noEmit` |
| `npm run clean` | Remove build output |

## Project structure

```
tic-tac-toe/
â”œâ”€â”€ src/
â”‚   â”œâ”€â”€ components/   # UI components
â”‚   â”œâ”€â”€ lib/          # Game logic & AI helpers
â”‚   â”œâ”€â”€ App.tsx       # Root component
â”‚   â”œâ”€â”€ main.tsx      # Entry point
â”‚   â”œâ”€â”€ types.ts      # Shared types
â”‚   â””â”€â”€ index.css     # Global styles
â”œâ”€â”€ assets/           # Static assets
â”œâ”€â”€ index.html        # HTML shell
â””â”€â”€ vite.config.ts    # Vite configuration
```

## License

This project is open source.
