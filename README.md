# Webassembly Sudoku solver

See https://mlbright.github.io/sudoku/.

The UI for this repository was copied and modified slightly from the one in https://emerentius.github.io/sudoku_web/.

I wanted to test my own [Sudoku solver library][lib], which is slower than [emerentius's][emerentius], so prefer his to mine.

## Build

```bash
wasm-pack build --target no-modules
```

[lib]: https://github.com/mlbright/sudoku-norvig-rs
[emerentius]: https://github.com/Emerentius/sudoku
