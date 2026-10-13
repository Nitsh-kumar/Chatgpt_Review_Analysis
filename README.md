# ChatGPT Review Analysis

An exploratory NLP notebook for studying sentiment and subjectivity in user reviews.

**Status:** analysis exercise. TextBlob scores are heuristic outputs; this project is not a trained or validated sentiment classifier.

## Workflow and files

- [Chatgpt_Customer_Reviews.ipynb](Chatgpt_Customer_Reviews.ipynb): data preparation, sentiment/subjectivity scoring, and plots.
- [chatgpt_reviews.csv](chatgpt_reviews.csv): included dataset file.

The notebook currently loads a CSV from a Statso URL rather than the checked-in CSV. Record and reconcile the exact input snapshot before comparing results. Dataset rights and representativeness have not been established.

## Environment

The notebook imports pandas, TextBlob, Swifter, Matplotlib, and Seaborn. It contains a Swifter installation cell but no shared pinned environment.

For a local exploratory session, create an isolated environment and install those dependencies plus Jupyter. Open the notebook, review the data-source cell, and run from a fresh kernel. Provider keys are not required by the reviewed notebook.

## Interpretation

TextBlob polarity ranges from negative to positive. Subjectivity ranges from more objective to more subjective; it does not mean positive/negative sentiment or user satisfaction.

The current subjectivity labeling needs correction. Plot semantics and preprocessing should also be checked before publishing conclusions. Do not infer overall user satisfaction, causal effects, or model quality from these reviews alone.

## Reproducibility checklist

Record the dataset source/version, row counts before and after cleaning, missing-value handling, score definitions, and plot denominators. Manually inspect a sample of labeled reviews and report observed failure cases.

See [project status](docs/PROJECT_STATUS.md).

## Validation

This documentation was checked against repository files on 13 October 2026. Notebooks, application runs, refreshes, and test suites were not executed during this documentation pass. Saved outputs are historical evidence, not a fresh run.
