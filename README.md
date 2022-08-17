Project Upward Mobility
==============================

Communities can foster environments for citizens to thrive and boost their upward mobility.  The conditions most local to a family are also most critical to achieve mobility from poverty.  Mobility from poverty includes economic success, power and autonomy, and being valued in a community.  To measure how upwardly mobile a community is, there are three key drivers tied to the definition: 

* Strong and health families
* Supportive communities
* Opportunities to learn and earn

Each driver has evidence-based metrics associated with it that can highlight the strengths and weaknesses of a community, and track progress on goals to improve the lives of its residents. These metrics can then inform community leaders where priorities should be to ensure that citizens have the opportunity to reach their full potential and be well-rounded individuals. 

This project was inspired and has intended to follow the research report [Boosting Upward Mobility: Metrics to Inform Local Action](https://www.urban.org/research/publication/boosting-upward-mobility-metrics-inform-local-action)

Getting Started
------------
### Census API Key
An API key is required to pull data via the Census API in the following notebooks: 

* NOTEBOOK
* NOTEBOOK
* NOTEBOOK

Sign up for a key at this [link](https://api.census.gov/data/key_signup.html)

### Requirements

There are three parts to this project:
* Data collection, manipulation and analysis
* django website front end - contained in sub repo 'djangosite @ c6f2e1f '
* Streamlit data visualization app - contained in sub repo 'streamlitapp @ 0931e5a'

Each part has it's own requirements.txt

Project Organization
------------

    ├── README.md          <- The top-level README for using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
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
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
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


Project Structure
--------
![Project Structure ](https://github.com/laurenrwolf/project-upward-mobility/blob/main/references/capstone%20pipeline.png?raw=true)

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
