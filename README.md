<div align="center">

# ♟ BlitzMind – A Simple Yet Smart C++ Chess Game  
[![C++](https://img.shields.io/badge/language-C%2B%2B17-blue.svg)](https://en.cppreference.com/w/cpp/17)
[![SDL2](https://img.shields.io/badge/library-SDL2-ff69b4)](https://www.libsdl.org/)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey)](https://github.com)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-WIP-yellow.svg)](https://github.com)
[![Game](https://img.shields.io/badge/genre-Chess-critical)](https://en.wikipedia.org/wiki/Computer_chess)
</div>


### 📋 Table of Contents
- [Introduction](#-introduction)
- [Features](#-features)
- [How to Play](#-how-to-play)
- [Credits](#-credits)

---

## 🧠 Introduction

I've always been a big fan of chess, so I decided to create my own version — *ChessAutoBot*. The game is developed with **C++** and **SDL2**, incorporating sound effects, custom UI, and an AI opponent based on **Minimax with Alpha-Beta Pruning**.

The AI is roughly equivalent to an **Elo 2000** and can evaluate up to **10 moves ahead**. While keeping the original chess rules intact, I also implemented advanced mechanics like **castling**, **en passant**, and **pawn promotion**.

All the sprites were custom-repainted by me using **Piskel** (yep, it’s free!), inspired by some designs I found online. And yes, I had to DIY because... student life 😅

---

## ✨ Features

### 🎮 Main Menu
- Choose game mode
- Toggle background music
- Exit game  

### 🧩 Game Modes
- Play vs AI (bot)
- Two-player local mode
- Return to main menu

### ♟ Gameplay
- Turn-based chess with visual guidance
- AI engine using **Minimax + Alpha-Beta Pruning**
- Full support for:
  - Castling
  - En passant
  - Promotion (select 1–4 for Queen, Rook, Bishop, Knight)
---

## 🕹️ How to Play

- **Move pieces**: Click and drag to the highlighted squares
 
- **Promote pawn**: Press 1 → 4 to promote  
  - 1 → Queen  
  - 2 → Rook  
  - 3 → Bishop  
  - 4 → Knight  

- **Toggle Music**: Press `M`
  
- **Return to Menu**: Press `Esc`

---

## 🙌 Credits

- **Sound effects** from [Chess.com](https://www.chess.com/)
- **Fonts** from [Google Fonts](https://fonts.google.com)
- **Sprites** drawn and edited using [Piskel](https://www.piskelapp.com/)

---

Thanks for checking out *BlitzMind*. Hope you enjoy playing it as much as I enjoyed building it!  
Feel free to reach out if you want to talk more about C++, game dev, or chess ♟
