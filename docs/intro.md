# Algorithmics & Data Structures

Welcome to the seminar for **Algorithmics & Data Structures**. Each week, you will be provided with a slide deck summarising the theoretical concepts covered in the seminar session, as well as a Jupyter Notebook. Solutions will be distributed on Fridays via Moodle and can be discussed in class, but will not be published here.

## Overview

| # | Seminar topic | Slides | Seminars |
|---|---------------|--------|---------|
| 1 | Welcoming Session & Getting Started | [Slides ↗](./_static/slides/en/01_environment_setup.html) | [Session](./seminars/en/01_environment_setup.ipynb) |
| 2 | Python Basics I: Control Structures | [Slides ↗](./_static/slides/en/02_python_control_structures.html) | [Session](./seminars/en/02_python_control_structures.ipynb) |
<!-- | 3 | Python Basics II: Data Structures | [Slides ↗](./_static/slides/en/03_python_data_structures.html) | [Session](./seminars/en/03_python_data_structures.ipynb) | -->
<!-- | 4 | Transfer Workshop & Project Kickoff | [Slides ↗](./_static/slides/en/04_project_kickoff.html) | [Session](./seminars/en/04_transfer_workshop.ipynb) |
| 5 | Data Structures | [Slides ↗](./_static/slides/en/05_data_structures.html) | [Session](./seminars/en/05_data_structures_impl.ipynb) |
| 6 | Algorithmic Complexity | [Slides ↗](./_static/slides/en/06_algorithmic_complexity.html) | [Session](./seminars/en/06_algorithmic_complexity.ipynb) |
| 7 | Sorting and Searching | [Slides ↗](./_static/slides/en/07_sorting_searching.html) | [Session](./seminars/en/07_sorting_searching.ipynb) |
| 8 | Trees and Graphs | [Slides ↗](./_static/slides/en/08_trees_graphs.html) | [Session](./seminars/en/08_trees_graphs.ipynb) |
| 9 | Problem Solving I: Basics | [Slides ↗](./_static/slides/en/09_problem_solving_I.html) | [Session](./seminars/en/09_problem_solving_I.ipynb) |
| 10 | Problem Solving II: Advanced | [Slides ↗](./_static/slides/en/10_problem_solving_II.html) | [Session](./seminars/en/10_problem_solving_II.ipynb) |
| 11 | Algorithmics Backup / Project | [Slides ↗](./_static/slides/en/11_backup_project.html) | [Session](./seminars/en/11_backup_project.ipynb) |
| 12 | Python Best Practices | [Slides ↗](./_static/slides/en/12_python_best_practices.html) | [Session](./seminars/en/12_python_best_practices.ipynb) |
| 13 | Introduction to Code Review | [Slides ↗](./_static/slides/en/13_code_review.html) | [Session](./seminars/en/13_code_review.ipynb) |
| 14 | Exam Review & FAQ | [Slides ↗](./_static/slides/en/14_exam_review.html) | [Session](./seminars/en/14_exam_review.ipynb) |
| — | Example disabled row | *Coming soon* | *Coming soon* | -->


## Running the notebooks locally

```bash
# 1. Clone the repository
git clone https://github.com/alho94/algorithmics-docs-public.git
cd algorithmics

# 2. Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Open the Notebooks in your fav IDE or launch Jupyter Lab
jupyter lab docs/seminars/en/
```

## Recommended but not mendatory references

- Cormen, Leiserson, Rivest & Stein — [*Introduction to Algorithms* (4th ed., MIT Press)](https://moodle.unige.ch/)
- Runestone Academy — [Problem Solving with Algorithms and Data Structures using Python](https://runestone.academy/ns/books/published/pythonds/index.html)
- [Python documentation](https://docs.python.org/3/)
- A very good reference to start with ANY computer science topic is roadmap.sh. This course will cover topics from:
  - [Python Roadmap](https://roadmap.sh/python)
  - [Data Structures & Algorithms Roadmap](https://roadmap.sh/datastructures-and-algorithms)

![Python Roadmap](/docs/_static/images/roadmap_python.png)

:::{important} Disclaimer
This website was developed with the friendly assistance of Claude and has been reviewed and approved by the instructor. The French version was automatically translated for convenience and may contain minor inaccuracies; in case of doubt, the English version prevails. Please report any errors or unclear passages — they will be corrected. 
:::
