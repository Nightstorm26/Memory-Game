# Memory Game

**Browser-based Memory Card Game — lightweight matching puzzle built with HTML, CSS & vanilla JavaScript**


<!-- Badges: key topics -->

[![memory-game](https://img.shields.io/badge/topic-memory--game-blue?style=flat-square)](https://github.com/topics/memory-game) [![javascript](https://img.shields.io/badge/language-javascript-yellow?style=flat-square)](https://github.com/topics/javascript) [![html](https://img.shields.io/badge/language-html-orange?style=flat-square)](https://github.com/topics/html) [![css](https://img.shields.io/badge/language-css-blueviolet?style=flat-square)](https://github.com/topics/css) [![responsive](https://img.shields.io/badge/responsive-design-green?style=flat-square)](https://github.com/topics/responsive-design) [![accessibility](https://img.shields.io/badge/accessibility-aria-lightgrey?style=flat-square)](https://github.com/topics/accessibility)


**Topics:** `memory-game` `matching-game` `web-game` `javascript` `html` `css` `frontend` `vanilla-js` `responsive-design` `accessibility` `puzzle-game` `browser-game` `beginner-friendly` `localstorage`


A simple browser-based memory (matching) game built with HTML, CSS and JavaScript.

Players flip over pairs of cards to find matching images. The game tracks moves, time, and provides a final score. It's designed to be lightweight and easy to extend or theme.

## Demo

Open `index.html` in your browser to play locally:

1. Clone or download the repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).

## Features

- Clean, responsive UI (HTML + CSS)
- Matching gameplay with animated card flips (JavaScript)
- Move counter and timer
- Restart button to play again
- Easy to change card images or layout

## How to Play

1. Click a card to flip it over.
2. Click a second card to try to find its match.
3. If the two cards match, they remain face-up; otherwise they flip back down.
4. Continue until all pairs are found.
5. Try to finish with the fewest moves and the fastest time!

## File Structure (typical)
- index.html — main page
- styles/ or css/ — CSS files
- js/ or scripts/ — JavaScript game logic
- assets/ or images/ — card images and other media

(Adjust these paths if your repository differs.)

## Installation / Local Development

No build tools are required — the game is static.

1. Clone the repo:
   git clone https://github.com/Nightstorm26/Memory-Game.git
2. Open `index.html` in your browser:
   - double-click `index.html`, or
   - run a local static server (recommended for testing):
     - Python 3: `python -m http.server 8000` then visit `http://localhost:8000/`
     - Node: `npx http-server` then visit the printed URL

## Customization

- Change the card images: replace files in the `assets/images` (or similar) folder and update the image references in the JS.
- Change board size: update the card generation logic in `js/<your-script>.js` to use more or fewer pairs.
- Styling: edit `css/styles.css` (or main stylesheet) to change colors, fonts, and animations.

## Accessibility & Responsiveness

- Ensure images have appropriate alt text where applicable.
- Consider adding keyboard controls (arrow/tab + Enter) for users who can't use a mouse.
- Test at different viewport sizes — the layout should adapt for mobile and desktop.

## Contributing

Contributions are welcome! Suggestions:
- Improve accessibility (keyboard, ARIA)
- Add sound effects and settings to toggle them
- Add difficulty levels (board sizes)
- Add high-score persistence (localStorage)

To contribute:
1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes and open a Pull Request

## License

This project is provided under the MIT License. See LICENSE for details.

## Credits

Created by Nightstorm26.
