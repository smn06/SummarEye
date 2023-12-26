## SummarEye: Document Summarization with Self-Supervision

---

### Overview:

SummarEye is an innovative project that harnesses the power of self-supervision to generate abstractive summaries of text documents. This repository contains a robust solution for document summarization, allowing users to effortlessly distill the key information from lengthy texts.

---
Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
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
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------



### Features:

- **Self-Supervised Learning:** Utilize cutting-edge self-supervision techniques for enhanced document summarization.
  
- **Abstractive Summaries:** Generate concise and meaningful abstractive summaries that capture the essence of the document.

- **Flexibility:** Adapt the model to various document types, making it suitable for a wide range of applications.

- **State-of-the-Art Model:** Implement a state-of-the-art neural network architecture for superior performance.

---

### Getting Started:

1. Clone the repository:

    ```bash
    git clone https://github.com/smn06/SummarEye.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the demo script:

    ```bash
    python demo.py
    ```
---

### License:

This project is licensed under the [MIT License](LICENSE).

