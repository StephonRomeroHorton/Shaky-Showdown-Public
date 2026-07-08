# Shaky Showdown is a real-time browser quick-draw game where timing matters more than aim.

**Live demo:** https://shakyshowdown.netlify.app/

## Why This Is Interesting

Shaky Showdown turns a simple cowboy duel into a timing game: the gun constantly spins, so every shot can win the round or backfire on the shooter. It supports two-player private rooms in real time, with both players seeing the same countdown, draw phase, shot result, winner, and score. I built it as a self-taught full-stack project to practice real-time game state, multiplayer rules, and browser-based game feel beyond a standard CRUD app.

## Tech Stack

- React
- Vite
- Node.js
- Express
- Socket.IO
- CSS
- Netlify
- Render

## Technical Highlights

- **Server-owned multiplayer state:** room creation, player roles, ready states, countdown timing, round phase, hit results, winner selection, and scoring are coordinated through a backend authority so both players stay in sync.
- **Timing-based shot resolution:** the game resolves shots from a constantly rotating weapon, including opponent hits and self-hits, which makes the core challenge depend on synchronized timing rather than pointer accuracy.

## Source Availability

The full source code is private, but I am happy to share it on request with interested employers.
