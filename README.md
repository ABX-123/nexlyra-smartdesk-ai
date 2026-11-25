# Nexlyra Smartdesk AI

## Description

This project is a small AI/ML decision-support prototype for a software engineering and digital services company. The system will use support ticket details available at submission time to estimate whether a support ticket may exceed its target resolution time.

## Build Instructions

Since the project is incomplete, the only runnable file is the Exploratory Data Analysis notebook, to run it:
```
git clone https://github.com/ABX-123/nexlyra-smartdesk-ai.git
cd nexlyra-smartdesk-ai
cd notebooks
python -m jupyterlab
```
then open EDA.ipynb using jupyter lab.

## Project Structure

Regarding other files, this is how they are structured
```
smartdesk-ai/
  data/                 (original CSV file)
  notebooks/            (EDA)
  reports/              (data dictionary, summary, Written Tasks (explain, compare, draw, ...))
  screenshots/          (chart screenshots)
  README.md
```