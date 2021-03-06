# Directory Structure For Data Science Projects 

Build with init.sh
--------
```
├── config_venv.txt
├── data
│   ├── external
│   ├── figures
│   ├── interim
│   ├── processed
│   └── raw
├── docs
├── init.sh
├── LICENSE
├── Makefile
├── models
├── notebooks
│   ├── draft
│   ├── exploratory
│   ├── notebook2src
│   └── report
├── README.md
├── references
├── reports
│   └── figures
├── requirements.txt
└── src
    ├── data
    ├── features
    ├── models
    └── visualization
```    
Cookiecutter Data Science - directory structure with python
--------
```

├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- Make this project pip installable with `pip install -e`
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.testrun.org

```
    
# References

**[Good enough practices in scientific computing] (https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)**
**[Cookiecutter] (http://drivendata.github.io/cookiecutter-data-science/)**
A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.

