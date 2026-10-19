# Mission Impawsible

A two-player hot-seat board game: find Agent Goldie.

Play it here: https://gokul-raj.github.io/mission-impawsible/

Everything lives in `index.html` — the board map, both cat tokens, the logo
and all 72 cards are embedded, so the file runs offline with no dependencies.

## How to play

Two agents, one screen. Each starts with $500 at their own safe house.
Roll two dice and your cat walks the route; at a fork, click the dot you want.

- **Green spots** draw that location's task card. Judge the dare between
  yourselves, then press what actually happened.
- **Red spots** draw an inconvenience.
- Take the fifth card at a location and its **gold card** flips on the spot.
- One of the nine gold cards is **Agent Goldie**. Find her and the mission ends.

## Two devices

Open the site on both devices. One of you taps **Open a room** and reads out the
5-letter code; the other taps **Join a room** and enters it. The browsers then
connect directly to each other — there is no game server and no sign-up.

Whoever's turn it is drives: their dice, card choices and fork picks are sent to
the other screen. The waiting player sees the board, the cards and the cash
update live, but cannot roll until the turn passes.

Keep both tabs open; closing one ends the session.
