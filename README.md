# Xiangqi GIF Maker

Static browser app for GitHub Pages.

## Features

- Edit a Xiangqi board from scratch.
- Switch to play mode and make legal moves on the board.
- Import a game from Xiangqi FEN plus ICCS/UCCI coordinate moves such as `h2e2`.
- Render the position sequence to a GIF in the browser.
- Download the GIF or copy it to the clipboard in supported browsers.

## Run locally

Open `index.html` in a browser, or serve the directory with any static server.

## Deploy to GitHub Pages

Push these files to a GitHub repository and enable GitHub Pages for the branch.

## Import format

- FEN example:
  `rnbakabnr/9/1c5c1/p1p1p1p1p/9/9/P1P1P1P1P/1C5C1/9/RNBAKABNR`
- Side to move:
  `w` for red, `b` for black
- Move format:
  ICCS/UCCI coordinates like `h2e2 h9g7 e2e7`
