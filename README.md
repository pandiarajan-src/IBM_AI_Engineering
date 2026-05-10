# IBM AI Engineering

A comprehensive machine learning course covering supervised and unsupervised learning techniques with Python.

## Quick Start

This project uses [uv](https://docs.astral.sh/uv/) for dependency management.

1. **Install uv** (if not already installed)
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

2. **Create the environment and install dependencies**
   ```bash
   uv sync
   ```

3. **Run a notebook**
   - Open any `.ipynb` file in `C1_ML_with_Python/` using VS Code
   - VS Code will automatically use the `.venv` created by `uv sync`
   - Execute cells sequentially from top to bottom

4. **Explore the course**
   - Start with **1_Simple-Linear-Regression** for fundamentals
   - Progress through regression, classification, and clustering topics
   - See [AGENTS.md](AGENTS.md) for the full course structure

## Common uv Commands

| Task | Command |
|------|---------|
| Install / sync all dependencies | `uv sync` |
| Add a new package | `uv add <package>` |
| Remove a package | `uv remove <package>` |
| Run a script in the venv | `uv run python main.py` |
| List installed packages | `uv pip list` |
| Upgrade all packages | `uv sync --upgrade` |

## Project Structure

```
C1_ML_with_Python/          # Main course material (11 notebooks)
├── Regression              # Topics 1, 2, 6
├── Classification          # Topics 3, 4, 7, 8
├── Ensemble Methods        # Topic 9
└── Unsupervised Learning   # Topics 10, 11
pyproject.toml              # Project metadata and direct dependencies
uv.lock                     # Locked dependency graph (committed to version control)
requirements.txt            # Pinned flat list for direct pip installs (pip install -r requirements.txt)
```

## Key Technologies

- **Package Manager**: uv
- **ML Framework**: scikit-learn
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn, plotly
- **Geospatial / Clustering**: geopandas, contextily, hdbscan
- **Python**: 3.12.13+

## Learning Path

Each notebook is self-contained but recommended order is:
1. **Regression**: Build foundation with simple and multiple linear regression
2. **Classification**: Learn logistic regression, KNN, decision trees, and SVM
3. **Advanced**: Explore ensemble methods (Random Forests, XGBoost) and clustering

## For AI Agents

Refer to [AGENTS.md](AGENTS.md) for detailed guidance on project conventions, notebook structure, and development workflows.
