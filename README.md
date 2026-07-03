# todo-list | a notebook-style to-do list

A simple, single-file to-do list with a handwritten notebook look. No build tools, no backend — just open `index.html`.

## Features

- Add, edit, complete, and delete tasks
- Filter by all / pending / completed
- Progress bar with task count
- Export your tasks as a `.json` file (backup) and import them back
- Fully responsive, works on mobile

## Data storage

Tasks are saved in the browser's `localStorage`, tied to the domain you host it on. This means:

- Data persists across page reloads and browser restarts
- Data does **not** sync between different browsers or devices
- Data is cleared if you use private/incognito mode, or manually clear site data

Use the **Export .json** button to download a real backup file you can keep or move to another device, then **Import .json** to load it back in.

## Running locally

Just open `index.html` in any browser. No install, no dependencies.

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. Make sure `index.html` is in the root of the repo (or in a `/docs` folder).
3. Go to **Settings → Pages**.
4. Under "Branch", select `main` and the folder where `index.html` lives, then save.
5. Your list will be live at `https://<your-username>.github.io/<repo-name>/`.

## Tech

Plain HTML, CSS, and JavaScript. Fonts: [Caveat](https://fonts.google.com/specimen/Caveat), [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans), and [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) via Google Fonts.# todo-list
