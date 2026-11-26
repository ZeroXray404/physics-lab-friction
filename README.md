# Physics Lab – Friction

Experimental investigation of friction on an inclined plane using Python and scientific data analysis.

## Objective

Investigate how the friction force changes with the inclination angle and normal force acting on a wooden block.

## Technologies

- Python
- uv
- pandas
- NumPy
- plotnine
- Jupyter Notebook
- Ruff

## Installation

```bash
uv sync --locked
```

Open `analysis.ipynb` in VS Code and select the project's `.venv` under **Select Kernel → Python Environments**.

`.python-version` pins the full Python version because VS Code can report `3.13.x` for a uv environment created with a minor-only pin and save `3.13.-1` in the notebook metadata.
If your `.venv` was created with the old pin, rename it to `venv.bak`, run `uv sync --locked` again, and reload the VS Code window before selecting the kernel.

## Project structure

- `data/` – Original experimental measurements
- `figures/` – Generated scientific visualizations
- `analysis.ipynb` – Data processing, calculations and statistical analysis

## Analysis

- Normal force
- Kinetic friction force
- Coefficient of friction
- Linear regression
- Pearson correlation coefficient
- Coefficient of determination
- Measurement uncertainty

## Purpose

This project revisits a previously completed physics laboratory experiment to develop practical skills in scientific programming, statistical analysis and reproducible data visualization.