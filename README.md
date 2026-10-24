# TWISTED — mobile-first prototype

**Choices. Mysteries. Mind Games.**

This is the first playable web prototype for TWISTED. It is designed mobile-first and can be hosted as a static site, including on GitHub Pages. Core gameplay and progress work locally; the service worker provides a basic offline cache after the first successful visit over HTTPS.

## Included in this prototype
- Twisted Choices: choose a response and see a thoughtful explanation.
- Case Closed: investigate fictional cases and identify contradictions.
- Mind Games: logic questions and riddles.
- Local XP, progress statistics, settings, and a mobile-first layout.
- PWA manifest, icon, and basic service worker.

## Important: what is not connected yet
- No real ads are active. The labelled ad areas are placeholders only.
- No AdMob IDs or SDK are included.
- No online leaderboard, account system, cloud sync, or community voting.
- This is not yet a Google Play release package.

## Publish the web prototype with GitHub Pages
1. Create a **new public repository** named `twisted-game` in your GitHub account.
2. Upload the files in this folder to the repository root (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, and `README.md`).
3. In the repository, open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. Its address will look like `https://YOUR-USERNAME.github.io/twisted-game/`.

If your repository is private, check the hosting eligibility for your GitHub plan before using Pages.

## Next: Android and Google Play
A sensible next stage is to package the tested app with Capacitor, create an Android project, and integrate Google's official Mobile Ads SDK through a suitable Capacitor plugin. Use test ad IDs during development and replace them only after the app is correctly configured. Review current Google Play testing, target API, privacy, consent, and app-content requirements before release.

## Content and product notes
- The cases are fictional; contradictions are clues, not proof of guilt.
- Keep ads separate from gameplay controls and never encourage ad clicks.
- Before public launch, review content suitability, accessibility, privacy disclosures, and all platform policies.
