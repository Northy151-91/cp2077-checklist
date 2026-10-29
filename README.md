# Ghost Netrunner Checklist — Gear v3

GitHub Pages-ready PWA for Cyberpunk 2077 Update 2.5 and Phantom Liberty.

## What's new
- Gear tab reorganised into 10 cyberware body parts, plus Weapons and Quickhacks.
- Every implant/weapon/quickhack shows target slot, level/quest availability, how to get it, and purpose.
- Separate **Obtained** and **Equipped** checkbox for each non-empty slot.
- Locked and intentionally empty slots clearly labelled.
- Collapsible body groups, quick jump chips and progress filter.
- Existing level / Relic / collectibles tracked as before.
- Compatible with v2 localStorage records and v2 JSON backup import.
- Updated service worker cache key to pick up the new version on GitHub Pages.

## Install/update on GitHub Pages
1. Export your progress backup from Gear before updating.
2. Put `index.html`, `manifest.webmanifest`, `sw.js` and both icons in the repository root.
3. Enable GitHub Pages from `main` / `(root)`.
4. Refresh the site (if old layout persists, close the app and reopen it twice).
5. Re-import the backup only if browser/device storage was cleared or changed.

Do not upload only the ZIP to Pages. The ZIP contains the website source files.

## Data
Browser localStorage key is unchanged; new gear tasks migrate old exact-match v2 gear completions to **Obtained** but do not pretend previous general purchases were also equipped.

## Known constraints
Available tiers depend on character level; cyberware capacity is variable. The guide is a target loadout rather than a guarantee that all recommended implant tiers can be bought at level one.
