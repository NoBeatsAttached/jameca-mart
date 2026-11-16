# JAMEKAS: Graveyard Shift

A Final Fantasy IV–style turn-based RPG set inside JAMECA-MART, a corner store in 1994 South Central LA.
You play Jamekas, the night clerk. Hold it down from 10 PM to 6 AM while the night crew walks in one after another, then take on Big Money Marcus.

Plays in your phone's browser. Open `index.html`, or turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Controls
- **Touch:** on-screen D-pad, A, B, START, MUSIC
- **Keyboard:** arrows/WASD move, Z/Space = A, X/Esc = B, Enter = START, M = music
- **Bluetooth/USB controller:** pair it with your phone, open the game in the browser, press any button. Standard mapping (D-pad/left stick, A/Cross, B/Circle, Start, Select = music).

## How it plays
- Walk the store. Shelves, coolers, slushie machine, coffee and the hot dog roller restock every hour. Sparkles show what's ready.
- Register = save. START = menu (items, status, save, music).
- Every fight you win moves the clock an hour. Level up to unlock skills: Mop Slap, Wet Floor, Hot Coffee, Price Check, Slow Jam, Boombox Blast, Call Manager.

## Updates
No refreshing needed. The game checks `version.json` every 90 seconds and whenever you come back to the tab. When a new build is pushed, an orange **NEW UPDATE - TAP** banner shows up. Tap it and the game saves and reloads to the new version. You can also check from START → UPDATE. Every build bumps `VERSION` in `index.html` and `version.json` together.
