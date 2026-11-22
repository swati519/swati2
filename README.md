# GAME ZONE

A responsive, browser-based mini-game arcade demo built with HTML, CSS, and vanilla JavaScript.

## Run locally

Open `index.html` in a modern browser, or serve this directory with any static HTTP server. No build step is required.

## Included

- Twelve playable mini-games: color and number prediction, spin wheel, lucky draw, dice, Ludo sprint, quiz, number guessing, memory cards, bubble pop, snake, and a sliding puzzle.
- Browser-local player profiles, coin balance, activity history, and demo leaderboard.
- A local admin preview for viewing profiles, activity totals, and hiding/showing games.
- Responsive dark arcade UI with keyboard-friendly controls and reduced-motion support.

## Important demo limitations

This is a **frontend-only prototype**, not a production account or administration system. Profiles and passwords are stored in browser `localStorage` and are not securely authenticated; use only throwaway demo credentials. Data is limited to the current browser and is not shared between visitors or devices. The leaderboard is sample/demo data. Admin controls are not protected and only modify the local view. The ad placement is a placeholder; no advertising provider is integrated.

Coins are virtual, free gameplay points only. They cannot be purchased, redeemed, or converted into money or prizes. Some prediction games spend virtual coins for the round and award virtual coins for a correct result, strictly as game mechanics.

Before a public launch, replace browser-local profile handling and admin controls with a secure backend and authorization, add proper server-side validation and abuse controls, and integrate any advertising provider in compliance with its current policies. Never collect payment details for these virtual coins.
