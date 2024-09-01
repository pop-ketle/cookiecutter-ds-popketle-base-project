{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
---

    .
    ├── LICENSE
    ├── README.md   <- The top-level README for developers using this project.
    ├── configs <- Setting files e.g. model parameter
    ├── data
    │   ├── features    <- Intermediate data.
    │   ├── input   <- Raw data.
    │   ├── logs    <- Log files
    │   └── output  <- Output data.
    ├── docs    <- Document folder e.g. Sphinx docs
    ├── models  <- Trained models
    ├── requirements.txt    <- Requirement file for the environment.
    ├── setup.py    <- makes project pip installable (pip install -e .) so src can be imported.
    └── src <- Source code
        ├── __init__.py
        ├── experiments <- folder for experiment.
        │   ├── code    <- experimental code like Jupyter Notebook.
        │   ├── description.md  <- 
        │   └── reports <- Generated analysis reports as HTML, PDF, LaTeX, etc.
        │       └── figs    <- Generated figures and other files to be used in reporting
        ├── tests   <- Test code
        └── utils   <- Utility code

---

Project based on the cookiecutter
* Inspired cookiecutter data science project template. #cookiecutterdatascience

---

### Usage of Rye
```
# Rye Initialization
rye sync

# Add library
rye add numpy

# Show library list
rye list

# Need Sync to use library
rye sync

# Remove library
rye remove numpy

# Run on Rye virtual environment
rye run python --version
```