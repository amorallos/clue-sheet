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

1. Download `index.html`.
2. Open it in any modern browser (Chrome, Safari, Firefox, Edge).

### Using it on your phone

There are two ways. Hosting the file (Option B) is more reliable, especially on iPhone.

#### Option A: Open the downloaded file

1. **Download** `index.html` to your phone, or download it on a computer and send it to your phone by AirDrop, email, a messaging app or a cloud drive (iCloud Drive, Google Drive, Dropbox).
2. **Save it** to your phone's Files app (iPhone) or Downloads folder (Android).
3. **Open it:**
   - **Android:** open the Files or Downloads app, tap `index.html` and choose **Chrome** if asked.
   - **iPhone:** open the Files app and tap `index.html`. If it shows as plain text or the buttons don't work, use Option B instead. iOS often can't run local HTML files properly.
4. Add players and start marking the grid.

Saved progress may not persist between visits when a page is opened from a local file, depending on your phone and browser. If your players disappear after you close the page, use Option B.

#### Option B: Host it and add it to your home screen

1. Host the file, for example on GitHub Pages (see above) or Netlify Drop, so you have a web address.
2. Open that address on your phone.
3. Add it to your home screen:
   - **iPhone (Safari):** tap the Share button, then **Add to Home Screen**, then **Add**.
   - **Android (Chrome):** tap the **⋮** menu, then **Add to Home screen** (or **Install app**), then confirm.
4. Open it from the new icon. It runs full screen like an app, and your progress is saved in that browser on your phone.

### Hosting it yourself

Because it is one static file, you can host it anywhere that serves HTML, such as GitHub Pages, Netlify or any web server. 

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
