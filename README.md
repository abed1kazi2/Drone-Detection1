# 🚁 Sentinel — Drone Detection System

A fully in-browser drone detection web app powered by YOLOv8 + ONNX.  
**No server needed. Runs entirely in your browser.**

🔗 **Live Demo**: `https://YOUR_USERNAME.github.io/drone-detection/`

---

## How It Works

- Model runs via **ONNX Runtime Web (WebAssembly)** — 100% client-side
- No data is sent to any server — everything stays in your browser
- Upload your trained `best.onnx` file and detect drones instantly

## Features

- 📷 Upload image and detect drones, persons, vehicles
- 🎯 Adjustable confidence and IoU thresholds
- 📊 Per-class detection counts
- 🖼️ Annotated output with bounding boxes

## Usage

1. Export your trained model: `python scripts/5_export.py --format onnx`
2. Open the site
3. Click **Choose best.onnx** and load your model
4. Upload an image and click **Run Detection**

## Local Development

Just open `index.html` in a browser — no build step needed.
