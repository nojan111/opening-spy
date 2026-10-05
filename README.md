# Opening Spy ♟

**Snoop on anyone's chess openings.** Type a Chess.com or Lichess username and see what they play, how often, and how it goes for them. Then open any game and replay it with Stockfish, an accuracy score, the clocks, and a slightly judgy little coach.

👉 **Live: https://nojan111.github.io/opening-spy/**

## Runs on your device. Even offline.

There's no server and no account. Stockfish runs right inside your browser, on your own phone or computer:

- **Engine eval, best lines, accuracy, blunder detection and the coach all work offline.** Nothing gets sent anywhere to be analysed.
- **The app itself opens without internet** after your first visit. Add it to your home screen and it behaves like a real app.
- **The only thing that needs a connection is loading someone's games**, since those come straight from the public Chess.com and Lichess APIs. Once they're loaded you can go offline and keep reviewing.

## What it does

- **Opening stats** for any player: every opening they use, how many games, what % of their games, win %, W/D/L. Filter by color and time control (bullet, blitz, rapid, daily/classical).
- **Every game in an opening, one tap away.** Pick the Sicilian and see every Sicilian they've played.
- **Board replay** with move sounds, swipe to step through moves on a phone, and an eval bar with the number on it.
- **Opening names as the game unfolds**: 1.e4 King's Pawn → 2...c5 Sicilian → the exact variation, plus where they left theory.
- **Accuracy** for both players, with blunders (??), mistakes (?) and inaccuracies (?!) marked. Shows Chess.com's own accuracy too when the game was reviewed there.
- **Eval graph** of the whole game, so you can see where it turned. Tap it to jump to that moment.
- **Clocks** for every move, plus time spent per move, so you can tell a blunder from a time scramble.
- **The coach**, a little pawn who explains why White or Black is better when you ask, and comments on every mistake with what went wrong, what was better, and a bit of attitude.

## Credits

- **Stockfish 10** (compiled to JavaScript by Niklas Fiekas), GPL-3.0. Because it's bundled, this project is also GPL-3.0 (see `LICENSE`).
- **chess.js** 0.10.3 by Jeff Hlywa, BSD-2-Clause.
- **Chess pieces** by Cburnett (Wikimedia Commons), CC BY-SA 3.0, via cm-chessboard by shaack.
- **Opening names** from the lichess-org/chess-openings dataset, CC0.
