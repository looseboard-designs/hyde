# Looseboard Hyde

Share the story. Keep the spot.

Hyde lets you share a photo of what you found without giving away where you found it. It strips the location data from a photo and replaces the background. Everything runs on your device; nothing is uploaded.

This repository holds the browser prototype.

## Files

- `index.html`: the app.
- `model.b64.txt`: the subject cutout model (U2-Net small), stored as base64 text.
- `ort-wasm-simd.wasm`: ONNX Runtime Web 1.17.3, the engine that runs the model.

## Running it

The files must be served from a web address. Opening `index.html` straight from a folder will not load the model.

## Status

Prototype. Tested in a desktop browser. Not yet verified on phones.
