# Nandini's Birthday Scrapbook 💌

A personalized birthday website for Nandini, made by Mehul. Built with plain HTML, CSS, and JavaScript. No build tools, frameworks, or paid hosting required.

## Included
- Password-style opening screen
- Scrapbook/paper aesthetic with tape, pinned Polaroids, and pastel details
- Personal birthday letter
- Three-photo gallery
- Clickable surprise gifts
- Confetti and floating decorations
- Tap-to-start synthesized music
- Mobile-friendly responsive layout
- GitHub Pages-ready `index.html`

## 1. Personalize it
Open `index.html` in a text editor and find `PERSONALIZE HERE` near the bottom.

Change:
```js
const CONFIG = {
  password: "nandini",
  photos: [
    { src: "images/memory1.jpg", caption: "A favourite memory 💗" },
    { src: "images/memory2.jpg", caption: "One for the scrapbook 🌷" },
    { src: "images/memory3.jpg", caption: "More memories to come ✨" }
  ]
};
```

- Change `password` to a secret word you both know.
- Add three photos to `images/` named `memory1.jpg`, `memory2.jpg`, and `memory3.jpg`, or update the paths to match your files.
- Update captions and the birthday letter text in the HTML.
- Preview by opening `index.html` in a browser.

### Security note about the password
The password screen is a fun reveal, not real security. The password and page content are included in the client-side HTML/JavaScript, so anyone who knows how to inspect the source can find them. Do not use it to protect sensitive/private content. GitHub Pages itself is public hosting.

## 2. Publish using GitHub Pages
1. Sign in at https://github.com/new and create a repository called `nandini-birthday-surprise`.
2. For the easiest setup, make the repository **Public**.
3. Upload `index.html`, `README.md`, and the `images` folder.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then click **Save**.
7. Wait for deployment. The published URL usually looks like:
   `https://YOUR-USERNAME.github.io/nandini-birthday-surprise/`

## 3. Test before sharing
- Try the correct and incorrect password.
- Check all three photos load on a phone.
- Tap the music button (browsers require user interaction before audio playback).
- Tap each gift and the final wish.
- Share the live link in WhatsApp.

## Privacy
GitHub Pages is public. Anyone with the link may view the page and photos. Only publish images and messages that Nandini would be comfortable sharing.
