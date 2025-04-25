# rockPaperScissorsLizardSpock

An implementation of the game *Rock, Paper, Scissors, Lizard, Spock* in LaTeX.

Yes, really.

## How to Play

To play the game:

1. Choose one of the following options: `rock`, `paper`, `scissors`, `lizard`, or `spock`.
2. Input your choice into the `\main{}` function in the `.tex` file.
3. Compile the file using your `pdflatex`.

If your input is valid, the compilation will generate a PDF showing:
- The rules of the game,
- Your choice,
- The computer's randomly generated choice,
- And the result (who won).

## Features

- 🎨 **Custom TikZ graphics** — All images are original and hand-drawn using TikZ.
- 🎲 **Randomized computer plays** — The computer selects its move at random with each compilation.
