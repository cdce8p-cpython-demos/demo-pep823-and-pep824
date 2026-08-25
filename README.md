# PEP 823 and PEP 824 Demo

Interactive WebAssembly demo showcasing PEPs 823 and 824 in Python.

## Features

- 🚀 Live Python REPL running in your browser
- 📦 Interactive examples

## Try It Live

Visit the demo at: https://pep823-and-pep824-demo.pages.dev

## Running Locally

```bash
python server.py
```

Then open http://localhost:8000/ in your browser.

## Technical Details

- Built with Emscripten (WASM)
- Python 3.16 with custom implementation
- Requires `SharedArrayBuffer` support (enabled via CORS headers)

## Credits

- Python WebAssembly build
- Demo template originally created by Pablo Galindo Salgado
