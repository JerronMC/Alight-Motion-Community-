# AM Community Creator Studio V4

An independent Alight Motion learning hub with tutorials, editing references, interactive planning tools, progress tracking, and community resource links.

## Project files

- `index.html` — page structure and interface content.
- `style.css` — all three original stylesheet sections combined in their original order, plus static presentation rules moved out of HTML attributes.
- `script.js` — the application logic, lesson data, tool interactions, local saving, and UI behavior.
- `assets/README.md` — notes about externally loaded visual/media resources.

## Run it

1. Extract the ZIP.
2. Open `index.html` in a modern browser such as Chrome.
3. For the most reliable video/embed behavior, use a simple static web server or host the folder on a static hosting service.

No build step or package installation is required.

## Internet and storage

The page can run as local files, but external videos, official support links, and the remote app-icon image require an internet connection. Learning progress, favorites, notes, preferences, and other saved workspace data use browser `localStorage` on the current device/browser. The built-in idea board is local-only, not a shared live community feed.

## Identity and brand note

This is an independent fan-made learning resource and is not the official Alight Motion app or an official community product. Product names, logos, and linked third-party resources remain the property of their respective owners. The logo image is loaded from a remote image URL rather than bundled as an asset.

## Quick maintenance notes

- Add or edit presentation rules in `style.css`.
- Add or change lessons, tool logic, and interactions in `script.js`.
- Change the page metadata, section structure, and accessible labels in `index.html`.
- Keep the three files together in the same folder so the relative paths work.
