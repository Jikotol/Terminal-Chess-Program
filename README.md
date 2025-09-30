# Terminal Chess Program 

## ✏️ Description
A fully ASCII CLI chess program written in python. Built as a personal project for Hack Club's Summer of Making and my CS50P Final Project 👏😃. Includes all standard rules (en passant, castling, endgames, etc). Play against a bot or with yourself<sub>(though that might get quite lonely)</sub>.

## 🎮 Features
- **Official Chess Notation Commands**- play using standard chess moves
- **Edge Case Handling**- all rules and scenarios are covered
- **Retro-esque Text Vibes**- gotta love the ASCII
- **En Passant**- <ins>en passant</ins>

## 💻 Instructions to Run

```
# Open a terminal
# Run pip install chess-som

# Make sure the file environment has access to chess_som
from chess_som import UI

ui = UI()

ui.start(game_mode="random") # or "player"
```
