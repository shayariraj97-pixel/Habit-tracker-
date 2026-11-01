# Habit Tracker

A single-page habit tracker designed to run in a modern mobile browser.

## Run it

1. Open `index.html` in a browser, or publish this repository with GitHub Pages.
2. The app stores habit progress in the browser's `localStorage` under the key `jee26`.
3. Use the same browser and site address to keep seeing the same saved progress.

## Included features

- Home, Habits, Chapters and Stats sections
- Monthly habit grid and habit consistency graph
- Category styling for Study, Fitness, Mind and Bad
- Study completed-tick colour: `#16A34A`
- Section-based habits with proportional progress and animated fill
- Default `Don't` habit in the Bad category
- Gun Park-inspired motivational quote styling

## Files

- `index.html` — complete app source (HTML, CSS and JavaScript in one file)
- `assets/dont-icon-reference.jpeg` — reference copy of the supplied Don't icon

The Don't icon is also embedded in `index.html`, so the app does not need the separate image file to display it.

## Important data note

Habit progress is saved locally in the browser on the device. Uploading this repository to GitHub does **not** upload or back up your personal habit records. Clearing browser data, changing browsers, or using a different site address may make the locally saved progress unavailable. Export/backup functionality is not included in this version.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, the `assets` folder and this `README.md`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish and open the URL it provides.

## Use on a Samsung Galaxy Tab A9+

Open the GitHub Pages URL in Chrome or Samsung Internet on the tablet. You can use the browser menu to add the page to the Home screen if that option is available.

This repository is a web app. It is not an Android APK or a native Android Studio project. Packaging it as an APK would require an additional Android wrapper/build setup.
