# Clue Detective Sheet

A simple, mobile-friendly detective sheet for the board game Clue / Cluedo, with named players. It is a single HTML file with no dependencies, no build step and no tracking.

Not intended to offer an advantage over those using the traditional paper sheets.

## Features

- Four editions: Clue Classic, Clue 2016-2022, Clue 2023 and Clue Master
- Add, rename, remove and reorder players (up to 8)
- Tap-to-cycle marks: ✓ has it, ✗ doesn't have it, ? maybe, blank
- Cross off cards you have ruled out
- Dark and light themes
- Progress saved in your browser, so you can close the page and come back
- Works offline once you have the file
- Responsive layout with sticky card names for small screens

## Getting started

No installation is needed.

1. Download `clue-sheet.html`.
2. Open it in any modern browser (Chrome, Safari, Firefox, Edge).

To use it on your phone, send the file to your device and open it in the browser. If you host the file somewhere, you can also use "Add to Home Screen" to open it like an app.

### Hosting it yourself

Because it is one static file, you can host it anywhere that serves HTML, such as GitHub Pages, Netlify or any web server. Rename the file to `index.html` if your host expects that.

## Usage

1. **Pick an edition** from the dropdown.
2. **Add players:** type a name and press **Add player** or Enter. A blank name becomes "Player 1", "Player 2" and so on.
3. **Edit players:** rename a player in their column header, remove them with **Remove**, or reorder them with the ◀ ▶ buttons or by dragging the ⠿ handle onto another column. Marks move with the player.
4. **Mark the grid:** tap a square to cycle through ✓, ✗, ? and blank.
5. **Cross off a card:** tap its name on the left. Tap again to undo.

### Controls

| Control | What it does |
| --- | --- |
| Clear marks | Removes all marks and crossed-off cards, keeps players |
| New game | Removes all players and marks, after a confirmation |
| Theme | Switches between dark and light |

Changing the edition keeps your players and marks and clears the crossed-off cards.

## Data and privacy

Everything stays on your device. Players, marks and theme are stored in your browser's local storage. Nothing is sent anywhere. Clearing your browser data, or opening the file in a different browser, starts you fresh.

## Known limitations

- The Clue Master card list was written from memory and may not match your box exactly. Please check it and report or fix any differences.
- Saved data is per browser and per device and is not synced.

## Contributing

Suggestions and fixes are welcome. Open an issue or pull request, especially for edition card lists that don't match the physical game.

## Acknowledgements

Inspired by [lowlydba/clue-sheet](https://github.com/lowlydba/clue-sheet), a Clue / Cluedo detective sheet site. This project does not use its code.

Clue / Cluedo is a trademark of Hasbro. This project is an unofficial fan tool and is not affiliated with or endorsed by Hasbro.

## Disclaimer

This project was created with the help of [Claude](https://claude.ai), an AI assistant made by Anthropic. The code and this documentation were generated and revised through conversation with Claude and may contain mistakes. Review it before relying on it, and test it on your own devices.

## License

Released under the MIT License. Add a `LICENSE` file with the full text, or change this section to the license you prefer.
