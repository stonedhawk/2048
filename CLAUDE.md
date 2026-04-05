# 2048

A browser-based 2048 puzzle game with smooth animations and a classic aesthetic. Single HTML file, React + Babel via CDN, zero build step.

## What we're building

- 4x4 grid, each cell is a tile slot
- Warm beige/tan page background (#faf8ef)
- Header: "2048" title, score box, best score box, "New Game" button
- Classic tile color palette per value (2, 4, 8, 16, 32, 64, 128, 256, 512, 1024, 2048+)
- Arrow key AND swipe input for tile movement
- Slide and merge logic: tiles slide to far end of row/column, same-value adjacent tiles merge (once per move)
- New tile spawns after each valid move (value 2 or 4, weighted toward 2)
- Score: add merged tile value; best score persisted in localStorage
- Game over: no empty cells and no adjacent matching tiles
- Win: any tile reaches 2048 (one-time overlay, "Keep Going" or "New Game")
- Smooth animations: slide translate, spawn scale-in, merge pop
- Touch/swipe support with 30px minimum threshold
- Responsive layout for mobile screens
- Signature: "Created by Stonedhawk (Rahul)" bottom-right, 11px, #b0a898

## Tech

- React 18 + Babel standalone (CDN)
- HTML5, CSS-in-JS via inline styles
- Single index.html file, no build step

## Constraints

- No em dashes in comments or text
- Keep code clean and well-commented
- Playable on desktop (Chrome, Firefox, Safari) and mobile
- No dependencies beyond React + Babel CDN
