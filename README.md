# Ship Stability Lab

Ship Stability Lab is a small browser app for learning how ship stability changes when weight is added, removed, or transferred.

## Open the app

Open [index.html](/Users/andriaevars/Documents/Codex/2026-04-20-can-you-make-me-an-app/index.html) in a browser.

## What it does

- Lets you enter your own ship data: displacement, beam, draft, KM, KG, TCG, and a target minimum GM.
- Simulates loading or removing weight.
- Simulates transferring weight vertically and transversely.
- Shows updated GM, list angle, displacement, and an approximate GZ at 10 degrees.
- Draws a simple ship diagram and an approximate small-angle GZ curve for teaching.

## Important note

This is an educational tool, not a substitute for approved stability books, class rules, or professional naval architecture calculations.

## Shareable link with GitHub Pages

This folder is set up for GitHub Pages publishing.

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Make sure your default branch is `main`.
4. In GitHub:
   Go to `Settings` -> `Pages`.
5. Under `Build and deployment`, set `Source` to `GitHub Actions`.
6. Push to `main` and wait for the `Deploy GitHub Pages` workflow to finish.

Your shareable link will usually be:

`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/`

If you want a cleaner custom link, you can later connect a custom domain in the GitHub Pages settings.

## Share with Android and iPhone users

The app is now set up like a lightweight installable web app.

### Android

1. Open the published GitHub Pages link in Chrome.
2. Tap the browser menu.
3. Choose `Install app` or `Add to Home screen`.
4. The app can then launch full-screen from the home screen.

### iPhone and iPad

1. Open the published link in Safari.
2. Tap the `Share` button.
3. Choose `Add to Home Screen`.
4. The app will open like an app icon from the home screen.

### Important

- The installable experience only works from a real `https://` link, not from a local `file://` path.
- The service worker provides basic offline loading for the main app files after the first visit.
