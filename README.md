# Game of life in c
This is my own implementation of [Conway's game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), made with C and [raylib](https://github.com/raysan5/raylib).

<div>
  <figure>
    <img src="/images/conway-gol.png" width="400">
  </figure>
  <img src="/images/conway-gol-1.png" width="400">
</div>

## Requirements
- C compiler (CC)
- Make
- Raylib 5.0

## Setup
### Linux
```sh
git clone https://github.com/felistron/game-of-life.git
cd game-of-life
make
./build/main
```

### Windows and MacOS
Not implemented yet

## Controls
- [SPACE] Pause/Play generation
- [G] Enable/Disable grid
- [H] Enable/Disable heatmap
- [R] Restart and fill with random cells
- [C] Clean all the cells
- [ENTER] Next generation
- [LEFT_CLICK] Put a live cell
