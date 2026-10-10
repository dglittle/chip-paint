# Chip Paint

Paint pixels that become logic gates and wires, then watch the signals run.

Live: https://dglittle.github.io/chip-paint/

## How it works

Every pixel's color is a part of the circuit:

- **wire** (yellow): carries a signal, bright when on
- **AND** (blue), **OR** (orange), **NAND** (magenta) gates
- **cross** (black): lets two wires cross without touching
- **toggle** (cyan): a switch you click to flip

Pick a brush from the toolbar and paint. The slider sets the speed of the
simulation. The whole simulation runs on the GPU (WebGL2).

## Run it

It's one file with no dependencies. Open `index.html` in a browser.
