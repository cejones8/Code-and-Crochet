# Code & Crochet

Math and code for **planned pooling**, a crochet technique where yarn that changes color at consistent intervals is worked back and forth to produce regular geometric patterns.

## Paper

**Predicting Planned Pooling Patterns** (Bridges 2024)

The paper identifies three desirable pattern families (flattened diamonds, square diamonds, and elongated diamonds) and proves formulas for choosing the row length L, given a color sequence of length n, that guarantee each one. For example, L ≡ ±1 (mod n) produces flattened diamonds. [PDF in this repo](Predicting_Planned_Pooling_Patterns___Bridges_2024.pdf)


## What's in this repo

- `crochet-color-pooling.html` and the `.js` / `.css` files: interactive pattern previewer
- `CrochetingCalculationsColorama.py`: pooled crochet pattern generator
- `Predicting_Planned_Pooling_Patterns___Bridges_2024.pdf`: the paper

## Run it

- **Web previewer:** download the repo and open `crochet-color-pooling.html` in a browser.
- **Python script:** `pip install colorama`, then `python CrochetingCalculationsColorama.py`

## Credits

The research and code were developed collaboratively by Cameron Barb, Ekaterina Birch, Jared Gonzalez, Claire Jones, Josh Makela, Abigail McClennan, and Lauren Wiermanski, advised by Dr. Laura Taalman, Department of Mathematics, James Madison University.
