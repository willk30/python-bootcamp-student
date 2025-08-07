# Python Bootcamp for ISE & OR PhD Students

A comprehensive 6-block intensive session designed to teach Python fundamentals for quantitative research to incoming Industrial & Systems Engineering and Operations Research PhD students.

**Instructor:** Will Kirschenman (wkkirsch@ncsu.edu)  
**Date:** August 7, 2025  
**Institution:** North Carolina State University

**Time Now:** 2:44 PM

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/) ← **Recommended: Use Google Colab for all notebooks**

## 🚀 Quick Start

### Option 1: Open Individual Notebooks (Recommended)

Click the "Open in Colab" badges below to open notebooks directly in Google Colab:

| Block | Topic | Colab Link |
|-------|-------|------------|
| **Block 1** | Programming Mindset & Python Setup | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/willk30/python-bootcamp-student/blob/main/notebooks/block1.ipynb) |
| **Block 2** | Essential Data Wrangling with NumPy & Pandas | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/willk30/python-bootcamp-student/blob/main/notebooks/block2.ipynb) |
| **Block 3** | From Data to Insights: Predictive Modeling | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/willk30/python-bootcamp-student/blob/main/notebooks/block3.ipynb) |
| **Block 4** | From Data to Decisions: Optimization Modeling | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/willk30/python-bootcamp-student/blob/main/notebooks/block4.ipynb) |
| **Block 5** | Essential Tools for Reproducible Research | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/willk30/python-bootcamp-student/blob/main/notebooks/block5.ipynb) |

> **✅ Recommended Method:** Click any "Open in Colab" badge above to automatically open that notebook in Google Colab - no setup required! Each notebook is self-contained and can be run independently.

### Option 2: Local Development with VS Code

For those preferring a local development environment:

**Prerequisites**: 
- [Visual Studio Code](https://code.visualstudio.com/) 
- Git ([Windows](https://git-scm.com/download/win) | [Mac](https://git-scm.com/download/mac) | Linux: `sudo apt install git`)
- Python 3.9+ from [python.org](https://www.python.org/downloads/)

**Setup Steps**:
1. Clone repository: `git clone https://github.com/willk30/python-bootcamp-student.git`
2. Open folder in VS Code
3. Install Python extension
4. Install dependencies: `pip install -r requirements.txt`
5. Open `.ipynb` files in the `notebooks/` folder

## 🎯 Goals

This session achieves two primary objectives:

1. **Foundation Building**: Provide a solid foundation in Python for tackling quantitative coursework and research challenges common in both ISE and OR programs
2. **Tool Introduction**: Introduce powerful computational tools and advanced concepts that enhance research productivity and demonstrate modern scientific computing capabilities

## 📚 Repository Contents

### 📓 Interactive Notebooks (`notebooks/`)
- **`block1.ipynb`** - Programming Mindset & Python Setup
- **`block2.ipynb`** - Essential Data Wrangling with NumPy & Pandas  
- **`block3.ipynb`** - From Data to Insights: Predictive Modeling
- **`block4.ipynb`** - From Data to Decisions: Optimization Modeling
- **`block5.ipynb`** - Essential Tools for Reproducible Research

*Note: Block 6 is instructor-led demonstration and discussion - no notebook provided*

### 📑 Presentation Materials (`presentations/`)
- **`block1.pdf`** - Programming fundamentals presentation
- **`block5.pdf`** - Git version control presentation

### ⚙️ Setup Files
- **`requirements.txt`** - Python package dependencies
- **`.gitignore`** - Git ignore patterns for Python projects

## 🕐 Schedule

| Time | Block | Topic |
|------|-------|-------|
| 9:00 AM - 9:50 AM | **Block 1** | Programming Mindset & Python Setup |
| 10:00 AM - 10:50 AM | **Block 2** | Essential Data Wrangling with NumPy & Pandas |
| 11:00 AM - 11:50 AM | **Block 3** | From Data to Insights: Predictive Modeling |
| 1:00 PM - 1:50 PM | **Block 4** | From Data to Decisions: Optimization Modeling |
| 2:00 PM - 2:50 PM | **Block 5** | Essential Tools for Reproducible Research |
| 3:00 PM - 3:50 PM | **Block 6** | Advanced Topics & AI for Research Productivity |
| 3:50 PM - 4:00 PM | **Wrap-up** | Final Wrap-up & Concluding Remarks |

*10-minute breaks between sessions, 70-minute lunch break*

## 📋 Block Details

### Block 1: Programming Mindset & Python Setup
**Objective:** Understand programming's role in research and set up a functional Python environment

**Topics:**
- Programming paradigms: compiled, interpreted (Python), and JIT-compiled (Julia)
- Python's ecosystem for data science, machine learning, and optimization
- Google Colab for interactive development
- Python basics: variables, data types, and first code execution

### Block 2: Essential Data Wrangling with NumPy & Pandas
**Objective:** Learn to load, inspect, clean, and manipulate tabular data

**Topics:**
- Vectorized operations with **NumPy** arrays
- **Pandas** DataFrame for data analysis
- File reading and essential DataFrame operations
- Data cleaning and feature engineering

### Block 3: From Data to Insights: Predictive Modeling
**Objective:** Build and interpret machine learning models

**Topics:**
- **Scikit-learn** library and supervised learning framework
- Linear regression model building, training, and evaluation
- Model interpretation: coefficients, R², error metrics
- Cross-validation and model performance assessment

### Block 4: From Data to Decisions: Optimization Modeling
**Objective:** Formulate optimization problems and solve with different solvers

**Topics:**
- Mixed-Integer Linear Programming (MILP) concepts
- **Pyomo** modeling language
- Classic optimization problems (scheduling, resource allocation)
- Solver integration: open-source and commercial options

### Block 5: Essential Tools for Reproducible Research
**Objective:** Master version control for code management and collaboration

**Topics:**
- Version control importance for reproducibility
- **Git** core concepts: staging, commits, branches
- **GitHub** for remote repositories and collaboration
- Best practices for research code management

### Block 6: Advanced Topics & AI for Research Productivity
**Objective:** Explore advanced computational topics and modern AI tools for accelerating research

**Topics:**
- **High-Performance Computing Showcase**: Live demonstration of advanced computational techniques used in research
- **AI-Powered Development Tools**: Interactive demo of modern productivity tools:
  - IDE-based tools: GitHub Copilot, Cursor
  - CLI-based tools: Claude Code, Gemini CLI
- **Research Acceleration**: How AI tools can help with development, debugging, and research tasks
- **Open Q&A**: Interactive discussion about tools, research methodologies, and the PhD journey

*Note: This block is instructor-led with live demonstrations and open discussion*


## 🔧 Key Python Libraries Covered

- **NumPy** - Arrays & mathematical operations
- **Pandas** - Data analysis and manipulation
- **Matplotlib/Seaborn** - Data visualization
- **Scikit-learn** - Machine learning
- **Pyomo** - Optimization modeling
- **SciPy/Statsmodels** - Statistical computing

## 🚨 Troubleshooting

### Common Colab Issues

**Problem**: Package not found
```python
# Solution: Install missing packages
!pip install package_name
```

**Problem**: Files not persisting between sessions
- **Solution**: Not needed! Each notebook is self-contained and generates its own data

**Problem**: Runtime disconnected
- **Solution**: Runtime menu → Reconnect, then re-run cells

### Local Installation Issues

**Problem**: Package installation fails
- **Solution 1**: Update pip: `python -m pip install --upgrade pip`
- **Solution 2**: Use conda: `conda install package_name`
- **Solution 3**: Try: `pip install --only-binary=all package_name`

**Problem**: Jupyter notebook won't start
- **Solution**: Try: `python -m jupyter notebook`

## 🎓 Target Audience

Incoming PhD students in:
- Industrial & Systems Engineering (ISE)
- Operations Research (OR)  

**Experience Level:** All levels welcome - from programming beginners to those seeking Python-specific skills for research

## 📖 Educational Philosophy

- **Hands-on Learning:** Interactive Jupyter notebooks with immediate feedback
- **Research-Focused:** Examples and applications relevant to ISE/OR research
- **Progressive Complexity:** Building from fundamentals to advanced topics
- **Practical Application:** Real problems and modern development workflows
- **Tool Integration:** Modern development workflows and AI-assisted coding

## 🌟 After the Bootcamp

### Continue Learning
- Explore advanced topics in your research domain
- Practice with real datasets from your field
- Join Python/data science communities
- Contribute to open source projects

### Build Your Portfolio
- Create a GitHub account
- Upload your projects and research code
- Document your work with README files
- Showcase your computational skills

### Resources
- **Python Official Tutorial**: https://docs.python.org/3/tutorial/
- **Kaggle Learn**: https://www.kaggle.com/learn (Free courses)
- **Real Python**: https://realpython.com/ (Tutorials and guides)
- **Stack Overflow**: https://stackoverflow.com/ (Q&A community)

## 📧 Contact

**Will Kirschenman**  
Email: wkkirsch@ncsu.edu  
Institution: North Carolina State University

## 📄 License

This educational material is provided for academic use. Please cite appropriately if you use or adapt these materials.

---

*This bootcamp provides the computational foundation for success in ISE and OR graduate programs, emphasizing practical skills for both coursework and future research endeavors.*

**Happy coding! 🐍✨**