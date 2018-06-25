# Instacart Analysis

This repository is my attempt to perform EDA on Instacart data.

## Running jupyter notebook
Jupyter notebook could be run using `docker-compose up` command.
It should give a token to log in.

## Data
Data can be downloaded from [this page](https://www.instacart.com/datasets/grocery-shopping-2017).
It should be put into `src/data` folder.
At the time of analysis, my folder had these files:

* .gitignore
* aisles.csv
* departments.csv
* order_products__prior.csv
* order_products__train.csv
* orders.csv
* products.csv

## Data import
For this analysis, Postgres is used.
It runs as a docker container, so you don't have to worry about it.
Import it by running notebook, that exists in `prepare/put-to-sql.ipynb`.

## Analysis
Analysis could be found in `exploration.ipynb` notebook.

## Feedback
Any (literally - any) feedback is greatly appreciated.