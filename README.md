# 🃏 Blackjack Game (C++)

A simple console-based Blackjack game built using C++.

## 🚀 Features

* Player vs Dealer gameplay
* Random card generation
* Ace logic (1 or 11)
* Hit or Stand options
* Win / Lose / Tie result
* Replay option

## 🛠️ Tech Used

* C++
* STL (`vector`, `algorithm`)
* Random (`ctime`, `random`)
* Windows console (`windows.h` for colors)

## ▶️ Run

### Compile

```bash
g++ blackjack.cpp -o blackjack
```

### Execute

```bash
./blackjack
```

## 🎮 How to Play

* You get 2 cards, dealer gets 2 (one hidden)
* Choose:

  * `H` → Hit
  * `S` → Stand
* Try to reach **21** without going over
* Dealer draws until score ≥ 17
* Higher score wins

## ⚠️ Note

* Works on Windows only


