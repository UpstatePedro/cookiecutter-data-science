# Cookiecutter - PyTorch Semantic Segmentation

_A project structure for running and communicating PyTorch semantic segmentation workflows - heavily inspired by the [Cookiecutter Data Science project](http://drivendata.github.io/cookiecutter-data-science/)._


#### [Project homepage](https://github.com/UpstatePedro/cookiecutter-semantic-segmentation/)


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/UpstatePedro/cookiecutter-semantic-segmentation

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── intermediate   <- Intermediate data that has been transformed from its Raw form.
│   ├── master         <- Master file(s) providing the information needed to pull the raw data down
│   ├── prepared       <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── environment.yaml   <- The requirements file for reproducing the project anaconda environment
│
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── cli            <- Collection of all click commands for project CLI
│   │
│   ├── data           <- Logic for download and munging of (training) data
│   │   └── tests        <- Automated tests :)
│   │
│   ├── inference      <- Logic required for running models 'in production'
│   │   └── tests        <- Automated tests :)
│   │
│   ├── lib            <- Shared logic & utils
│   │   └── tests        <- Automated tests :)
│   │
│   ├── models         <- Logic for defining architectures & managing model instances
│   │   └── tests        <- Automated tests :)
│   │
│   ├── testing        <- Logic for evaluation of trained models
│   │   └── tests        <- Automated tests :)
│   │
│   ├── training       <- Scripts to turn raw data into features for modeling
│   │   └── tests        <- Automated tests :)
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── tests        <- Automated tests :)
│
└── tox.ini            <- tox file with settings for running tox; see tox.testrun.org
```
