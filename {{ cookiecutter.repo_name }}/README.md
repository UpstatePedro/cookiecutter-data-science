{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── master         <- Data from third party sources.
    │   ├── raw            <- The original, immutable data
    │   ├── intermediate   <- Intermediate data that has been transformed.
    │   ├── prepared       <- The final, canonical data sets for modelling.
    │   └── external       <- Data from third party sources
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models
    │
    ├── notebooks          <- Jupyter notebooks
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── environment.yml    <- The requirements file for reproducing the project environment
    │
    ├── results            <- Results data from trained models
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   │
    │   ├── cli            <- Defininition of command line interface for running tasks
    │   │
    │   ├── data           <- Logic for management of project data
    │   │
    │   ├── evaluation     <- Logic for evaluation of trained models
    │   │
    │   ├── lib            <- Logic & utilities to support other parts of the src package
    │   │
    │   ├── models         <- Model generation & model I/O
    │   │
    │   ├── training       <- Logic for training of models
    │   │
    │   └── visualisation  <- Scripts to create exploratory and results oriented visualisations
    │       └── visualise.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
