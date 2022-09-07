# WASM Checkers

WASM Checkers is a [checkers game](https://en.wikipedia.org/wiki/Checkers) (a.k.a. _draughts_) coded in WebAssembly text format (WAT).
These codes include only the core game logics and their tests through function calls from JS side.
You can check the test results in a dev console of your browser when you open the index.html via running HTTP server.

The guide of coding these programs is presented in the book ["Programming WebAssembly with Rust" by Kevin Hoffman](https://pragprog.com/titles/khrust/programming-webassembly-with-rust/).
But I made some minor changes to the original code to make it be compiled.

## How to run

Clone this repository, start an HTTP server, and open http://localhost:8000 in your browser.

```console
# Start an HTTP server. With Python3 installed, you can do:
python3 -m http.server
```

## License

MIT
