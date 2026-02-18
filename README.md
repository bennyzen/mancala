# Mancala

A web-based Mancala (Kalah) game against an AI opponent. Single HTML file, zero dependencies.

## Play

Open `index.html` in any browser, or [play online](https://bennyzen.github.io/mancala/).

## Features

- 3 difficulty levels: Easy (random), Medium (minimax depth 4), Hard (minimax depth 10 + alpha-beta pruning)
- Step-by-step animated sowing with visual highlights for captures and extra turns
- Sound effects via Web Audio API
- Rules dialog for beginners
- Mobile-friendly (landscape)

## Rules

Pick seeds from a pit on your side, sow them counter-clockwise one at a time. Land your last seed in your store for an extra turn. Land it in an empty pit on your side to capture the opposite pit's seeds. Most seeds wins.
