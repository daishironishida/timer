# Timer

A minimal countdown timer for the browser.

![idle state](https://via.placeholder.com/1x1)

## Features

- Circular progress ring that drains as time counts down
- Start, Pause, and Stop controls
- Settings drawer (⚙) to configure any duration
- Last used duration is remembered across page reloads
- OS notification when the timer finishes (requires HTTPS — works on GitHub Pages)
- Tab title changes to `* Done!` when the timer expires

## Usage

Open `index.html` in any browser. No build step, no dependencies.

To set a custom duration, click the **⚙** icon in the top-right corner.

## Deploying to GitHub Pages

1. Push `index.html` to a GitHub repository
2. Go to **Settings → Pages** and set the source to the `main` branch, root folder
3. Your timer will be live at `https://<your-username>.github.io/<repo-name>/`

> Browser notifications only work over HTTPS, so they will fire correctly once deployed.

## Browser support

Works in any modern browser (Chrome, Firefox, Safari, Edge).
