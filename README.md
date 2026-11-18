# Barracks-Web Games

A responsive, no-build static gaming website.

## Included
- Horse Racing with four editable horse names and randomized race speeds
- Reaction Test
- Number Guessing
- Local leaderboard (scores are saved in the visitor's browser)
- Responsive modern-minimalist design

## Preview locally
Open `index.html` in a modern browser. No dependencies or build step are required.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a **new public repository** named `barracks-web-games`.
2. Upload `index.html` to the repository's root (not inside another folder).
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the Pages deployment to finish. Your site will be at:
   `https://YOUR-GITHUB-USERNAME.github.io/barracks-web-games/`

GitHub Pages provides free hosting for public repositories. A custom domain is optional and usually costs money.

## Important leaderboard note
This first version uses browser `localStorage`, so scores are private to the browser/device that created them. A cross-device, shared leaderboard needs a database and a small backend/API. Do not treat local scores as verified competitive results.
