# Road Rush — Car Racing Game

This folder contains a lightweight, original HTML5 arcade racing game starter.

## Files
- `index.html` — the game and its controls
- `manifest.json` — PWA metadata
- `sw.js` — offline cache support after the first successful load over HTTPS

## Quick test on a phone
1. Keep all three files in the same folder.
2. Upload them to a static HTTPS host such as GitHub Pages.
3. Open the website once while online, wait for it to load, then try airplane mode.
4. If you update files, bump the cache name in `sw.js` (for example, `road-rush-v2`).

## Important before Play Store
This is a playable web-game prototype, not a signed Android App Bundle (AAB), and it has not been device-tested or reviewed by Google Play. To publish an Android app, you must package/build it as an Android app, test it, provide a store listing and privacy/data-safety declarations, and upload a signed AAB through Play Console. Google Play's current rules and account requirements apply. A Play Console account owner must be 18+; a parent/guardian should handle publishing if you are under 18. New personal developer accounts may need a closed test with at least 12 opted-in testers for 14 continuous days before production access.

## Monetization
Do not add ads until the game is tested and you have checked the ad network's current policies. Revenue is not guaranteed. Do not use copyrighted car logos, music, images, or assets without permission.
