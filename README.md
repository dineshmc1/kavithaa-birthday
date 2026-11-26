# A Universe Called Kavithaa

A cinematic, personal birthday experience built with React, Vite, React Three Fiber, Drei, Framer Motion, and Three.js.

## Run locally

```bash
npm install
npm run dev
```

## Personalize

- **Words, dates, choices, letter and garden messages:** edit `src/content.js`.
- **Photos:** place personal files in `public/photos/` and update the `gallery` entries in `src/content.js`.
- **Music:** add a licensed file at `public/music/romantic-instrumental.mp3`. It is never autoplayed.
- **GitHub Pages base path:** `vite.config.js` uses a portable `./` base, so assets work both at a repo Pages URL and a custom domain.

## Deploy to GitHub Pages

1. Create an empty GitHub repository and push this project to its `main` branch.
2. In **Settings → Pages**, select **GitHub Actions** as the source.
3. The included workflow builds and publishes automatically. GitHub will report the live HTTPS URL in the workflow run.
4. Create the QR code only after you have that live URL. Do not use localhost or a preview URL.

## QR delivery

The real public URL depends on the GitHub account and repository, so it cannot safely be pre-encoded. Once the site is live, generate a high-resolution QR image from that exact HTTPS URL, print it with the label: “A little universe, made just for you. Scan to enter. ♥” and scan-test it before printing.
