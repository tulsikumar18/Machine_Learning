# Machine Learning Project

This repository contains machine learning datasets and Jupyter notebooks for learning, practicing, and evaluating common machine learning techniques.

## Contents

- `LogisticRegression.ipynb` - Logistic regression example and workflow.
- `MachineLearning&Evaluation.ipynb` - General machine learning and model evaluation exercises.
- `Matplotlib.ipynb` - Data visualization practice using Matplotlib.
- `pandas.ipynb` - Data manipulation examples using pandas.
- `Encodings/` - Encoding technique notebooks and practice datasets.
- `Scaling/` - Feature scaling notebooks.
- CSV/TSV datasets such as `titanic.csv`, `Salary_Data.csv`, `movies_datset.csv`, `netflix.csv`, `uber.csv`, and more.

## How to use

1. Install Python and Jupyter on your machine.
2. Open the repository in VS Code or Jupyter Lab.
3. Run the notebooks interactively to explore the datasets and models.

## GitHub setup

1. Initialize a git repository (if not already initialized):
   ```bash
   git init
   ```
2. Create a `.gitignore` file to exclude files and folders that should not be committed.
3. Add files to staging:
   ```bash
   git add .
   ```
4. Commit the changes:
   ```bash
   git commit -m "Initial commit"
   ```
5. Add your GitHub remote repository:
   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   ```
6. Push to GitHub:
   ```bash
   git push -u origin main
   ```

## Ignore `.venv`

If you are using a virtual environment (such as `.venv`), you should not commit it. It is better to store dependencies in a `requirements.txt` file or similar.

Add the following to `.gitignore`:

```gitignore
.venv/
__pycache__/
.ipynb_checkpoints/
.DS_Store
```

## Remove `.venv` if not needed

If `.venv` is only a local environment for development and you do not need to keep it in the project, you can delete it safely:

```bash
rm -rf .venv
```

Then reinstall dependencies in a fresh environment if needed.

## Recommended workflow

1. Create or update `requirements.txt` if you have Python dependencies:
   ```bash
   pip freeze > requirements.txt
   ```
2. Add `.gitignore` and `README.md`.
3. Commit and push.

---

### Notes

- Keep notebooks and dataset files under version control.
- Keep local environment files like `.venv` out of git.
- If you need a new virtual environment later, recreate it with `python -m venv .venv`.
