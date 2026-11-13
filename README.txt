# Bloom — your personal study & reflection space

## What is included
- Personal diary with saved entries
- Daily to-do list and progress
- CLAT 2028 subject tracker
- Class 11 Commerce tracker
- Study prompt helper (copies a prompt to paste into ChatGPT)
- Comfort corner and mood check-in
- Goals and dream board
- Mobile-friendly app-like layout, offline caching, and install metadata

## Important privacy note
Your diary, tasks, goals and progress are stored in your browser's local storage on the device you use. They are not synced to another phone and can be lost if browser site data is cleared. Do not use this as a secure vault for highly sensitive information. The website does not send your diary entries to a server.

## Put Bloom online so you can add it to your phone
A Progressive Web App needs to be hosted on an HTTPS website to install reliably.

Beginner-friendly route using GitHub Pages:
1. Sign in to GitHub and create a new **public** repository named `bloom`.
2. Upload all four files from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS link on your Android phone in Chrome.
6. In Chrome, tap the three-dot menu → **Add to Home screen** (or **Install app**, if shown).

## Use it
Open Bloom and use the bottom navigation. Your entries save automatically when you press the relevant Save/Add button. For the Study Helper, write a topic, choose the kind of help you want, tap **Prepare my study prompt**, copy it, and paste it into ChatGPT. This starter version does not include a private AI API connection.

## Editing
You can change the app title, colours and text in `index.html`. Keep the filenames the same so the manifest and service worker continue to work.
