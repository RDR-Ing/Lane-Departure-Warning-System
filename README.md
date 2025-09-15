# Lane Departure Warning (LDW)

Short description: A Lane Departure Warning system for automotive research and prototyping. Includes classic CV pipeline, example videos, and evaluation scripts.

## Features
- Real-time lane detection (OpenCV-based)
- Unit tests, CI, and Dockerfile for reproducibility
- Scripts to download public datasets and prepare data

## Quick start
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python src/ldw/main.py --video data/sample/sample_road.mp4
