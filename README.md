# Monopoly Tracker

A mobile-first web app for tracking cash, properties, rent and game progress in Monopoly-style property-trading board games.

## Current MVP

- Add and manage players
- Track player cash balances
- Move money between bank and players
- Move money between players
- Assign property ownership
- Set house / hotel levels
- Mark properties as mortgaged
- Calculate and pay rent
- Keep a transaction log
- Undo the latest money transaction
- Export and import game data as JSON
- Store game data locally in the browser

## How it works

This first version is intentionally simple. It is a single static `index.html` file with no backend, login or database. Game data is saved in the browser using `localStorage`.

That means:

- The app works quickly on one device.
- Refreshing the page keeps the game state.
- Different devices do not automatically sync yet.
- Export/import JSON can be used to move a game between devices.

## Deployment

This project can be deployed directly on Vercel as a static site.

Recommended settings:

| Setting | Value |
|---|---|
| Framework Preset | Other |
| Build Command | Leave blank |
| Output Directory | Leave blank |
| Install Command | Leave blank |

## Future roadmap

Useful next features:

1. Buy property flow: select player, select property, deduct cost and assign ownership.
2. Trade builder for property and cash swaps.
3. Custom board setup.
4. Card/event shortcuts.
5. Supabase cloud sync for multi-device games.
6. Player join links or QR codes.

## Note

This is a fan/helper app for personal board-game tracking. It does not include official Monopoly artwork, official board design or official card text.