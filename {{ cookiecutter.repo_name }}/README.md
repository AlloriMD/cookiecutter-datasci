{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── .gitignore         <- Tells Git what to ignore
    ├── .env               <- Secrets (passwords) and config variables; excluded by .gitignore
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── environment.yml    <- The requirements file for reproducing the analysis environment
    ├── LICENSE
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── diary.md           <- Chronological log of daily progress made on the project.
    │
    ├── data
    │   ├── codebooks      <- Codebooks (data dictionaries) for data sets.
    │   ├── final_tidy     <- The final, canonical, and tidy data sets for modeling.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── data
    │   ├── protocols      <- Project protocols, documentation, including codebooks that I wrote.
    │   └── sphinx         <- Default Sphinx project à la Read the Docs -- see https://github.com/rtfd/sphinx_rtd_theme and http://sphinx-doc.org.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- References, publications, manuals, etc.
    │
    ├── products           <- All reports
    │   ├── figures        <- Graphics and figures to be used in reporting.
    │   ├── manuscripts    <- Manuscript (e.g., Word, Manuscripts, LaTeX, etc.).    
    │   ├── reports        <- Other reports, such as grant-funding updates.
    │   └── presentations  <- PowerPoint, etc.
    │
    │
    └── src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module
        │
        ├── data           <- Scripts to download or generate data
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions
        │   ├── predict_model.py
        │   └── train_model.py
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations
            └── visualize.py


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
