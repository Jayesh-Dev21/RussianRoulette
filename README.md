# Russian Roulette


<img src="https://upload.wikimedia.org/wikipedia/commons/1/1a/Rosyjska_ruletka.png" alt="Russian Roulette" width="300">

**играть** (“Play”)

## Overview

**Russian Roulette** is a terminal-based game of chance, guts, and glory. Face off against bots in a dangerous game where only one can survive. Outlast your opponents and earn virtual money with every pull of the trigger—but beware, one mistake ends it all.

> **Warning:** This game is for virtual thrills only. Do not try this in real life.

## Features

- Play against up to 5 bots, each with unique names.
- Randomized bullet chamber each round.
- Earn virtual money for surviving rounds and outlasting bots.
- ASCII banners for an immersive experience.

## Requirements

- GCC (for compiling the C code)
- Python 3 (for ASCII banners)
- Python package: `pyfiglet`

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Jayesh-Dev21/RussianRoulette.git
   cd RussianRoulette
   ```

2. **Install Python dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Build the game:**
   ```sh
   make
   ```
   This will generate an executable called `app`.

## Usage

Run the game from the terminal:
```sh
./app
```

You’ll be prompted to enter your name and presented with a menu:
- `0. Help` – Shows instructions and rules.
- `1. Play` – Start a game against bots.
- `2. Start New Game` – Reset progress and start over.
- `3. Exit` – Quit the game.

### Game Play

- Each round, the revolver’s chamber is loaded with a random number of bullets (1-6).
- Players and bots take turns pulling the trigger.
- Survive to earn $1000 each time; eliminate all bots to win a bonus!
- ASCII banners appear for various events (requires Python and pyfiglet).

## Cleaning Up

To remove the compiled binary, run:
```sh
make clean
```

## License

This project is licensed under the MIT License.
