# Genetic Variant Classification from Clinical Evidence Text

    ![Status](https://img.shields.io/badge/status-portfolio%20project-blue) ![Python](https://img.shields.io/badge/python-3.x-informational) ![NLP](https://img.shields.io/badge/NLP-relevant-lightgrey) ![Clinical Text](https://img.shields.io/badge/Clinical%20Text-relevant-lightgrey) ![Variant Classification](https://img.shields.io/badge/Variant%20Classification-relevant-lightgrey)

    Structured-plus-text modeling workflow with feature engineering and interpretable multi-class evaluation.

    ## Why this project matters
    This project shows thoughtful feature design, class imbalance handling and class-wise error review on biomedical text.

    ## Project purpose
    This repository documents a graduate portfolio project completed in healthcare or biomedical analytics. The goal was to build a workflow that is clear, reviewable and grounded in sound data handling rather than only optimizing for a headline model score.

    ## Project highlights
    - Combined structured mutation fields with clinical evidence text
- Normalized variant strings to reduce inconsistency and sparsity
- Built TF-IDF word and character n-gram features
- Reviewed class-wise errors and confusion patterns

    ## Dataset
    - **Dataset:** MSKCC variant interpretation dataset
    - **Task:** Multi-class classification of genetic variants using structured mutation fields and clinical evidence text

    ## Workflow
    1. Load structured fields and evidence text
2. Normalize variant representations
3. Build hybrid structured and text features
4. Train baseline classification models
5. Evaluate class-wise performance and confusion patterns

    ## Methods and tools
    - Python
- Pandas
- NumPy
- scikit-learn
- TF-IDF word n-grams
- TF-IDF character n-grams
- Class weighting
- Confusion matrix
- Multi-class evaluation

    ## Results
    Add final metrics, figures and short observations here.

    Suggested items to include:
    - main evaluation metrics
    - one figure or confusion matrix
    - one short note on common errors or limitations
    - one short note on what improved the workflow

    ## Repository structure
    - `notebooks/` project walkthrough and exploratory work
    - `src/` preprocessing, training and evaluation scripts
    - `outputs/figures/` saved charts, plots or confusion matrices
    - `outputs/metrics/` summary text or metric tables
    - `docs/` short project notes or exported summaries
    - `assets/` images used in the README if needed

    ## How to run
    ```bash
    pip install -r requirements.txt
    python src/preprocess.py
    python src/train.py
    python src/evaluate.py
    ```

    ## Notes
    - This repository documents a graduate portfolio project and is intended to present the workflow clearly for review
- Raw dataset files are not included in this repository
- Further model tuning and more detailed error analysis would be useful next steps
