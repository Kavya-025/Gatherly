# Gatherly — Event Discovery

A responsive event discovery and registration website built with semantic HTML, modern CSS, and vanilla JavaScript.

## Run locally

Open `index.html` in a browser, or serve the folder with any static web server. No build step or dependencies are required.

## Features

- Eight upcoming gatherings with individual detail views
- Add, edit, and remove gatherings in the on-page manager; cards, search, filters, and registration choices update immediately
- Live text search and category filters
- Registration form with name, email, phone, and event validation
- Events, successful registrations, and the selected theme are stored locally in the browser with Local Storage
- Light and dark themes, with the selected theme remembered
- Responsive layouts for mobile, tablet, and desktop
- Keyboard support for event cards and the `Ctrl/⌘ + K` search shortcut

## Project files

- `index.html` — page structure and dialogs
- `styles.css` — design system, responsive layouts, and motion
- `script.js` — event data, filtering, details, form validation, and local persistence

## Project links

- Live website: [https://kavya-025.github.io/Gatherly/](https://kavya-025.github.io/Gatherly/)
- GitHub repository: [https://github.com/Kavya-025/Gatherly](https://github.com/Kavya-025/Gatherly)

The website is published with GitHub Pages from the `main` branch at the repository root. Pushing updates to `main` automatically republishes the site.

## Notes

Event listings start as sample content. Use **Manage gatherings** below the event cards to add, edit, or remove listings. Those changes are saved in that browser's Local Storage and appear on reload, but are not shared with other visitors or devices. For a public multi-user event catalog, connect the site to a hosted database and admin authentication.

Photos load from Unsplash, and Google Fonts are used for typography, so those visual assets need an internet connection. Registration details also remain in the visitor's browser and are not sent to a server.
