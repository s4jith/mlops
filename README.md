# MLOps Practice Project

This repository contains daily machine learning practice tasks.
It includes datasets, Jupyter notebooks, and small apps.

## What Is Inside

- `dataset/` : CSV files and sample video data
- `Day 1` to `Day 8` : task-wise learning notebooks and code
- `Day 7/Task 17` : simple Flask app (`app.py`)
- `Day 7/Task 18` : frame extraction and JSON output

## Basic Setup (Windows)

1. Open terminal in project folder.
2. Create virtual environment:

```powershell
python -m venv .venv
```

3. Activate virtual environment:

```powershell
.\.venv\Scripts\Activate.ps1
```

4. Install packages (if `requirements.txt` exists):

```powershell
pip install -r requirements.txt
```

## How To Use

- Open and run notebooks inside each `Day X/Task Y` folder.
- For Flask app:

```powershell
cd "Day 7/Task 17"
python app.py
```

## Goal

Learn and practice ML concepts step by step with small daily tasks.