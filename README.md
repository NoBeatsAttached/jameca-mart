# JAMEKAS: Graveyard Shift

A Final Fantasy IV–style turn-based RPG set inside JAMECA-MART, a corner store on Florence Ave, South Central LA, 1994.
You play Jamekas, the night clerk. Five graveyard shifts, Monday to Friday. Somebody is paying crews to run every store off the block, and you're going to find out who.

## Story
1. **MONDAY - Clocking In.** Marcus's crew. Boss: Big Money Marcus.
2. **TUESDAY - New Hire.** Keisha joins the party. Boss: Lowrider Lou.
3. **WEDNESDAY - Lights Out.** Power's cut, so it's flashlight only. Boss: Deacon.
4. **THURSDAY - The Collector.** Men in suits. Boss: The Collector.
5. **FRIDAY - Last Call.** Final boss: Vance Sinclair (two phases).

## Explore 90s LA
Days are free roam. Nights are your shift, but you can step outside.
- **Florence Ave**: Walt's porch, Smitty's Cuts (boarded up), Benny's Pawn, Suds Laundry (boarded up), Tia Rosa's taco truck, the record store, the bus stop, and the park
- **Parking lot**: pumps, payphone, dumpster, a lowrider
- **Back alley**: fights day and night, crates to loot
- **Swap Meet** (take the bus): Uncle Ray's gear, Auntie Pearl's snacks, DJ Flex
- **Florence Park**: basketball court, lowrider show, BBQ
- **Benny's Pawn**: the SP-1200, $1500. Buy it to unlock Sample Flip and change the ending.

Each day has story objectives. Talk to Mr. Dee at the register to clock in. Side quest: clear the alley crew 3 times for Tia Rosa. Level carries over. New Game+ after the credits.

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
