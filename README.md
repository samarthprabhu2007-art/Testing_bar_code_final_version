# Code 128 Multi-Engine Scanner Comparison

A standalone, zero-build comparison testbed for Code 128 barcode scanning directly in the browser.

## Features & Supported Engines

1. **Quagga2**: Pure JavaScript / Web Worker based Code 128 decoder (`@ericblade/quagga2`).
2. **ZBar WASM**: WebAssembly port of the mature ZBar C library (`@undecaf/zbar-wasm`).
3. **Native BarcodeDetector**: Chrome / Android native Shape Detection API with zero overhead.

## How to Run

Simply open `index.html` in any modern browser (or serve it with a static server over HTTPS for mobile camera testing).
