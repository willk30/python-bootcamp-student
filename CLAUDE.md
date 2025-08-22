# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Python bootcamp repository designed for incoming PhD students in Industrial & Systems Engineering (ISE) and Operations Research (OR) at NC State University. The bootcamp is a comprehensive 5-block intensive session teaching Python fundamentals for quantitative research.

**Instructor:** Will Kirschenman (wkkirsch@ncsu.edu)  
**Date:** August 7, 2025  
**Institution:** North Carolina State University

## Repository Structure

```
python-bootcamp-student/
├── notebooks/           # Interactive Jupyter notebooks (5 blocks)
│   ├── block1.ipynb    # Programming Mindset & Python Setup
│   ├── block2.ipynb    # Essential Data Wrangling with NumPy & Pandas
│   ├── block3.ipynb    # From Data to Insights: Predictive Modeling
│   ├── block4.ipynb    # From Data to Decisions: Optimization Modeling
│   └── block5.ipynb    # Essential Tools for Reproducible Research
├── presentations/       # PDF presentation materials
│   ├── block1.pdf     # Programming fundamentals presentation
│   ├── block2.pdf     # Data wrangling presentation
│   ├── block3.pdf     # Machine learning presentation
│   ├── block4.pdf     # Optimization modeling presentation
│   └── block5.pdf     # Git version control presentation
├── requirements.txt    # Python package dependencies
├── .gitignore         # Git ignore patterns for Python projects
└── README.md          # Comprehensive project documentation
```

## Development Environment

### Primary Development Platform
- **Google Colab** (Recommended) - Pre-configured with most required packages
- Accessible at: https://colab.research.google.com/
- No local installation required

### Local Development (Optional)
For students preferring local development:
```bash
# Install dependencies
pip install -r requirements.txt

# Start Jupyter notebook
jupyter notebook
```

### Required Python Version
- Python 3.9 or higher

## Key Dependencies

The bootcamp uses these core libraries:

### Data Science Stack
- **numpy** >= 1.21.0 - Numerical computing and arrays
- **pandas** >= 1.5.0 - Data manipulation and analysis
- **matplotlib** >= 3.5.0 - Data visualization
- **scipy** >= 1.9.0 - Scientific computing
- **seaborn** >= 0.11.0 - Statistical visualization

### Machine Learning
- **scikit-learn** >= 1.1.0 - Machine learning library
- **statsmodels** >= 0.13.0 - Statistical modeling

### Optimization
- **pyomo** >= 6.4.0 - Mathematical optimization modeling
- **plotly** >= 5.10.0 - Interactive visualizations
- **highspy** >= 1.5.0 - HiGHS optimization solver

### Optional Commercial Solvers (Academic Licenses)
- **gurobi** >= 11.0.0 - Commercial optimization solver
- **cplex** >= 22.1.0 - IBM CPLEX optimization solver

## Working with Notebooks

### Running Notebooks
Each notebook is self-contained and includes:
- Package installation checks and dependency management
- Comprehensive explanations with theory and practical applications
- Progressive hands-on exercises building from basics to advanced concepts
- Real-world examples using synthetic PhD student research productivity data
- Interactive practice problems themed around academic life and research scenarios
- Self-generating datasets (no external data files required)

### Notebook Execution Order
1. **Block 1**: Python fundamentals, programming paradigms, Google Colab mastery, basic syntax and functions
2. **Block 2**: NumPy arrays, comprehensive Pandas data wrangling, complete data cleaning pipeline with feature engineering
3. **Block 3**: Scikit-learn machine learning pipeline, linear regression, model evaluation, cross-validation, and prediction interpretation
4. **Block 4**: Pyomo optimization modeling, MILP formulation, solver comparison, real-world decision problems
5. **Block 5**: Git version control fundamentals, GitHub workflow, professional development practices

### Data Generation and Flow
- **Block 1**: Simple simulation datasets (inventory, coffee consumption, parking)
- **Block 2**: Comprehensive PhD student dataset with realistic messiness (missing values, duplicates, outliers)
- **Block 3**: Self-contained data pipeline that recreates Block 2's cleaned dataset for standalone use
- **Block 4**: Multiple optimization datasets (time allocation, course scheduling, campus routing)
- **Block 5**: Project-based data for version control practice
- All datasets generated programmatically - no external files needed

## Educational Context

### Target Audience
- Incoming PhD students in ISE and Operations Research
- All experience levels welcome (beginner to intermediate)
- Focus on research-relevant Python applications

### Learning Objectives
1. **Foundation Building**: Solid Python foundation for quantitative coursework
2. **Tool Introduction**: Modern computational tools for research productivity
3. **Practical Application**: Real problems and development workflows
4. **Research Integration**: Examples relevant to ISE/OR research domains

### Block Topics
- **Block 1**: Programming paradigms (compiled vs interpreted), Python ecosystem, Google Colab shortcuts, variables, data types, control flow, functions, inventory simulation, PhD life exercises
- **Block 2**: NumPy vectorized operations, Pandas DataFrame manipulation, comprehensive data cleaning (missing values, duplicates, outliers, categorical standardization), feature engineering, GroupBy operations
- **Block 3**: Machine learning fundamentals, scikit-learn workflow, linear regression theory, train-test split, model evaluation metrics, cross-validation, feature importance, prediction intervals, PhD productivity modeling
- **Block 4**: Linear programming visualization, Pyomo modeling framework, MILP formulation, solver comparison (HiGHS, CBC, Gurobi, CPLEX), time allocation optimization, course scheduling, traveling salesman problem
- **Block 5**: Git workflow (working → staging → repository), essential Git commands, branching and merging, .gitignore creation, commit best practices, GitHub integration, statistical calculator project

## Common Development Tasks

### Package Installation in Colab
Most packages are pre-installed, but if needed:
```python
!pip install package_name
```

### Data Persistence in Colab
For saving work between sessions:
```python
from google.colab import drive
drive.mount('/content/drive')
```

### Running All Notebooks
Each notebook is independent but builds conceptually on previous blocks. Start with Block 1 for foundational concepts.

## Troubleshooting

### Common Colab Issues
- **Package not found**: Install using `!pip install package_name`
- **Runtime disconnected**: Reconnect via Runtime menu, re-run cells
- **Files not persisting**: Save to Google Drive using drive.mount()

### Local Installation Issues
- **Package installation fails**: Update pip with `python -m pip install --upgrade pip`
- **Jupyter won't start**: Try `python -m jupyter notebook`
- **Dependencies conflict**: Consider using conda environment

## Course Schedule

| Time | Block | Topic |
|------|-------|-------|
| 9:00 AM - 9:50 AM | **Block 1** | Programming Mindset & Python Setup |
| 10:00 AM - 10:50 AM | **Block 2** | Essential Data Wrangling with NumPy & Pandas |
| 11:00 AM - 11:50 AM | **Block 3** | From Data to Insights: Predictive Modeling |
| 1:00 PM - 1:50 PM | **Block 4** | From Data to Decisions: Optimization Modeling |
| 2:00 PM - 2:50 PM | **Block 5** | Essential Tools for Reproducible Research |
| 3:00 PM - 3:50 PM | **Block 6** | Advanced Topics & AI for Research Productivity |

## Repository Guidelines

### File Organization
- All educational content in notebooks/ directory
- PDF presentations for all 5 blocks complement interactive notebooks
- No external data dependencies (self-generating datasets)
- Comprehensive documentation in README.md

### Git Practices
- Educational repository - students encouraged to fork
- Clean commit history with meaningful messages
- Proper Python .gitignore patterns included
- No sensitive data or large files committed

### Commit Authorship
**IMPORTANT**: All commits in this repository must have Will Kirschenman as the sole author.
- **DO NOT** include Claude Code attribution lines in commit messages
- **DO NOT** add "🤖 Generated with [Claude Code]" lines
- **DO NOT** add "Co-Authored-By: Claude <noreply@anthropic.com>" lines
- Keep commit messages clean and professional for educational use
- This is an educational repository that should not show AI assistance in the git history

## Contact Information

**Instructor:** Will Kirschenman  
**Email:** wkkirsch@ncsu.edu  
**Institution:** North Carolina State University

## Additional Resources

- **Python Official Tutorial**: https://docs.python.org/3/tutorial/
- **Google Colab Introduction**: https://colab.research.google.com/notebooks/intro.ipynb
- **Kaggle Learn**: https://www.kaggle.com/learn (Free data science courses)
- **Real Python**: https://realpython.com/ (Python tutorials and guides)