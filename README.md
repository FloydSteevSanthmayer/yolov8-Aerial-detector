# YOLOv8 Ship Detector (Minimal)

**One-line:** Minimal, notebook-first repository for YOLOv8 ship detection with Label Studio annotation.

## Contents
This minimal repository contains the essential files to share or publish a Jupyter notebook-based project:

- `ADD_YOUR_NOTEBOOK.ipynb` — placeholder for the Jupyter notebook you will upload.
- `README.md` — this file with quick instructions.
- `requirements.txt` — list of Python packages needed to run the notebook.
- `dataset/ships.yaml` — example YOLO dataset YAML to show expected structure.
- `flowchart_colored.mmd` — Mermaid source for the pipeline flowchart.
- `flowchart_colored.png` — rendered flowchart (suitable for embedding in the README).
- `LICENSE` — MIT license.
- `.gitignore` — common ignores, including large files and env.
- `.env.example` — example environment variables (no secrets).

## Quickstart

1. Add your notebook: replace `ADD_YOUR_NOTEBOOK.ipynb` with your actual Jupyter notebook file.
2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
3. Follow the instructions in your notebook. Use `dataset/ships.yaml` as an example dataset descriptor for YOLO training.

## Notes
- This minimal bundle is ideal for demos and sharing via GitHub or Colab.  
- For production or collaborative projects, consider adding small scripts (`train.py`, `inference.py`), tests, and CI configuration later.
