# Algorithmics & Data Structures — Course Website

**University of Geneva — CUI Bachelor in Computer Science**
Built with [Jupyter Book v2](https://jupyterbook.org/) (MyST) · Deployed via GitHub Pages

---

## Live site

> <https://alho94.github.io/algorithmics>

---

## Repository structure

```
algorithmics/
├── myst.yml                    ← Jupyter Book v2 config (title, TOC, theme, nav)
├── docs/
│   ├── intro.md                ← Home page
│   ├── requirements.txt        ← Python dependencies for students
│   ├── _static/
│   │   └── custom.css          ← UNIGE red-brand styling
│   └── seminars/
│       ├── en/                 ← All 14 seminar notebooks (EN)
│       └── fr/                 ← French translations
└── .gitignore
```

---

## Running notebooks locally

```bash
# 1. Clone
git clone https://github.com/alho94/algorithmics-docs-public.git
cd algorithmics

# 2. Create a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r docs/requirements.txt

# 4. Launch Jupyter Lab OR work in your preferred IDE
jupyter lab docs/seminars/
```

The interactive widgets (`ipywidgets`) require **JupyterLab ≥ 4.0** (which includes widget support out of the box).

---

## Dependencies

| Package | Purpose |
|---------|---------|
| `jupyter-book` | Build static HTML from notebooks |
| `sphinx-togglebutton` | Collapsible hint/solution blocks |
| `ipywidgets` | Interactive sliders, buttons in theory cells |
| `ipympl` | `%matplotlib widget` backend |
| `matplotlib` | All visualisations |
| `numpy` | Numerical operations |
| `pandas` | Data manipulation examples |
| `streamlit` | Seminar 4 transfer workshop |
| `pytest` | Seminar 12/13 testing examples |
| `pylint`, `flake8`, `black`, `mypy` | Code quality demos |

---

## Contact

Course maintained by the CUI teaching team at the University of Geneva.
Questions → open a GitHub Issue on this repository.
