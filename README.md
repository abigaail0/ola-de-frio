# Predicción de Olas de Frío en Río Grande, Tierra del Fuego

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

### Las olas de frío pueden tener efectos severos en la población y en las infraestructuras. Este proyecto utiliza datos meteorológicos de Río Grande, Tierra del Fuego para entrenar un modelo de clasificación binaria que permite anticipar estos eventos y mejorar la toma de decisiones en climatología.

La ciudad de Río Grande está ubicada en una de las zonas más australes del país, y se caracteriza por un clima oceannico y alta frecuencia de eventos extremos de temperaturas mínimas, especialmente en invierno. Las olas de frío afectan no solo la salud pública, sino también sectores clave como la infraestructura, el transporte, la agricultura y la logística urbana. Es por esto que anticipar la ocurrencia de estos eventos permitirá optimizar alertas meteorológicas, planificar medidas preventivas ante riesgos climáticos y tomar decisiones estratégicas en el manejo energético y asistencial.
## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         prediccion_olas and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── prediccion_olas   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes prediccion_olas a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

