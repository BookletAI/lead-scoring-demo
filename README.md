# End-to-End Lead Scoring Example

Example data and code for [the end-to-end lead scoring tutorial](https://towardsdatascience.com/a-true-end-to-end-ml-example-lead-scoring-f5b52e9a3c80) on Towards Data Science.

Test out this [lead scoring model demo on Booklet.ai.](https://app.booklet.ai/model/lead-scoring)

## Setup

This example is build with Python `3.8.2`

```
python3 -m venv lead-scoring
source lead-scoring/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name=lead-scoring
```

Then start the MLFlow server:

```
mlflow server
```
