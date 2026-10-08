# War Card Game

A browser-based implementation of the classic card game War, built as a single HTML file with no dependencies.

## How to Play

Open `warcardgame.html` in any web browser.

### Rules

- A standard 52-card deck is shuffled and split evenly (26 cards each) between you and the CPU.
- Each round, both players flip their top card. The higher card wins both cards.
- **War:** If both cards are equal, each player places 3 cards face-down and flips a 4th. The higher face-up card wins all cards in the pot. Wars can chain if the flipped cards tie again.
- A player with fewer than 4 cards places as many face-down as they can, keeping their last card to flip. A player with no card left to flip loses the war and the pot.
- The game ends when one player holds all 52 cards.

### Card Values

Cards rank from lowest to highest: 2 3 4 5 6 7 8 9 10 J Q K A

## Controls

| Control | Action |
|---|---|
| **Flip Cards** | Play one round |
| **Auto Play** | Play rounds automatically |
| **Speed slider** | Adjust war and auto-play speed (1–10x) |
| **New Game** | Shuffle and restart |

## Features

- Green felt card-table aesthetic
- Animated win/loss highlights
- War pile display during tie rounds
- Round counter and live card counts
- Auto-play mode with variable speed
- Phone-friendly layout
