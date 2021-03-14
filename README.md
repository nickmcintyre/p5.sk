# p5.sk
> p5.js + Python in the browser

Hello! This project is an experiment aimed at bringing [p5.js](https://p5js.org/) to the [Skulpt](https://skulpt.org/) implementation of Python. It is a simple adaption of the official [Processing.js module](https://github.com/skulpt/skulpt/blob/master/src/lib/processing.js).

## Why not pyp5js?
[pyp5js](https://github.com/berinhard/pyp5js/) is a fantastic project with a friendly team. Their hard work enabled me to teach with p5.js + Python starting in January 2021. My students and I quickly realized the [Pyodide](https://pyodide.org/en/latest/) runtime was painfully slow to start on Chromebooks and similar devices. We also experimented with a [Brython](https://brython.info/) wrapper, but the lack of meaningful error messages made debugging far too difficult for beginners.

## Building

1. Install [Node.js](https://nodejs.org/).
2. Copy or clone the [Skulpt repository](https://github.com/skulpt/skulpt) to your machine.
3. Copy the [p5.js](/p5.js) file into the Skulpt repo's `src/lib` directory.
4. Open a terminal, navigate to the Skulpt repo's root directory, and run the commands `npm install` followed by `npm run dist`.

## Tinkering
1. Copy the [p5.html](/p5.html) file into the repo's `example` directory.
2. Run a web server from the repo's root directory (i.e., `python3 -m http.server`).
3. Open your browser and navigate to `localhost:8000/example/p5.html`.
