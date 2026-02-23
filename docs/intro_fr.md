# Algorithmique & Structures de données

:::{important} Attention
La traduction a été générée automatiquement à l'aide d'un LLM et n'a **pas** été révisée. En cas de doute, la [version anglaise](./intro.md) fait foi.
:::

Bienvenue dans le séminaire d'**Algorithmique & Structures de données**. Chaque semaine, vous recevrez un jeu de diapositives résumant les concepts théoriques abordés en séance, ainsi qu'un Jupyter Notebook. Les solutions seront distribuées le vendredi via Moodle et pourront être discutées en classe, mais ne seront pas publiées ici.

## Vue d'ensemble

| # | Thème du séminaire | Diapositives | Séminaires |
|---|-------------------|--------------|------------|
| 1 | Session d'accueil & Premiers pas | [Diapositives ↗](./_static/slides/fr/01_environment_setup.html) | [Séance](./seminars/fr/01_environment_setup.ipynb) |
| 2 | Bases de Python I : Structures de contrôle | [Diapositives ↗](./_static/slides/fr/02_python_control_structures.html) | [Séance](./seminars/fr/02_python_control_structures.ipynb) |
| 3 | Bases de Python II : Structures de données | [Diapositives ↗](./_static/slides/fr/03_python_data_structures.html) | [Séance](./seminars/fr/03_python_data_structures.ipynb) |
<!-- | 4 | Atelier de transfert & Lancement du projet | [Diapositives ↗](./_static/slides/fr/04_project_kickoff.html) | [Séance](./seminars/fr/04_transfer_workshop.ipynb) |
| 5 | Structures de données | [Diapositives ↗](./_static/slides/fr/05_data_structures.html) | [Séance](./seminars/fr/05_data_structures_impl.ipynb) |
| 6 | Complexité algorithmique | [Diapositives ↗](./_static/slides/fr/06_algorithmic_complexity.html) | [Séance](./seminars/fr/06_algorithmic_complexity.ipynb) |
| 7 | Tri et recherche | [Diapositives ↗](./_static/slides/fr/07_sorting_searching.html) | [Séance](./seminars/fr/07_sorting_searching.ipynb) |
| 8 | Arbres et graphes | [Diapositives ↗](./_static/slides/fr/08_trees_graphs.html) | [Séance](./seminars/fr/08_trees_graphs.ipynb) |
| 9 | Résolution de problèmes I : Bases | [Diapositives ↗](./_static/slides/fr/09_problem_solving_I.html) | [Séance](./seminars/fr/09_problem_solving_I.ipynb) |
| 10 | Résolution de problèmes II : Avancé | [Diapositives ↗](./_static/slides/fr/10_problem_solving_II.html) | [Séance](./seminars/fr/10_problem_solving_II.ipynb) |
| 11 | Algorithmique supplémentaire / Projet | [Diapositives ↗](./_static/slides/fr/11_backup_project.html) | [Séance](./seminars/fr/11_backup_project.ipynb) |
| 12 | Bonnes pratiques Python | [Diapositives ↗](./_static/slides/fr/12_python_best_practices.html) | [Séance](./seminars/fr/12_python_best_practices.ipynb) |
| 13 | Introduction à la revue de code | [Diapositives ↗](./_static/slides/fr/13_code_review.html) | [Séance](./seminars/fr/13_code_review.ipynb) |
| 14 | Révision d'examen & FAQ | [Diapositives ↗](./_static/slides/fr/14_exam_review.html) | [Séance](./seminars/fr/14_exam_review.ipynb) | -->

## Exécuter les notebooks localement

```bash
# 1. Cloner le dépôt
git clone https://github.com/alho94/algorithmics-docs-public.git
cd algorithmics

# 2. Créer et activer un environnement virtuel
python -m venv .venv
source .venv/bin/activate      # Windows : .venv\Scripts\activate

# 3. Installer les dépendances
pip install -r requirements.txt

# 4. Ouvrir les notebooks dans votre IDE ou lancer Jupyter Lab
jupyter lab docs/seminars/fr/
```

## Références recommandées (non obligatoires)

- Cormen, Leiserson, Rivest & Stein — [*Introduction to Algorithms* (4e éd., MIT Press)](https://moodle.unige.ch/)
- Runestone Academy — [Problem Solving with Algorithms and Data Structures using Python](https://runestone.academy/ns/books/published/pythonds/index.html)
- [Documentation Python](https://docs.python.org/fr/3/)
- Un très bon point de départ pour tout sujet en informatique est roadmap.sh. Ce cours couvre des thèmes issus de :
  - [Python Roadmap](https://roadmap.sh/python)
  - [Data Structures & Algorithms Roadmap](https://roadmap.sh/datastructures-and-algorithms)

:::{important} Attention
Ce site a été développé avec l'aide de Claude et a été vérifié et approuvé par l'enseignant. La version française a été traduite automatiquement pour des raisons pratiques et peut contenir des inexactitudes mineures ; en cas de doute, la version anglaise fait foi. Merci de signaler toute erreur ou passage peu clair — ils seront corrigés.
:::
