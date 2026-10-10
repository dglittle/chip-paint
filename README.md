# Logic Paint

Paint pixels that become logic gates and wires, then watch the signals run.

Live: https://dglittle.github.io/logic-paint/

## How it works

Every pixel's color is a part of the circuit:

- **wire** (yellow): carries a signal, bright when on
- **AND** (blue), **OR** (orange), **NAND** (magenta) gates
- **cross** (black): lets two wires cross without touching
- **toggle** (cyan): a switch you click to flip

Pick a brush from the toolbar and paint. The slider sets the speed of the
simulation. The whole simulation runs on the GPU (WebGL2).

## Run it

No dependencies: `index.html` plus `chip006.png`, the starting chip it loads.
Serve the folder (e.g. `python3 -m http.server`) and open it in a browser.
Opening `index.html` straight from disk won't load the starting chip, since
browsers block reading an image's pixels from `file://`.

## License

MIT
