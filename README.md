# ETF Analyzer, Module 7 Challenge

This is a JupyterLab notebook which utilizes SQL to read a given database. A data analyst may then use the database to read tables of data and filter the data to answer their questions.

---

## Technologies

This application was written in Python 3.9.12. This application is dependent on the [pandas](https://pandas.pydata.org/), [JupyterLab](https://jupyter.org/), [pyviz hvplot](https://hvplot.holoviz.org/), [numpy](https://numpy.org/), and [SQLAlchemy Lite](https://docs.sqlalchemy.org/en/14/dialects/sqlite.html).

---

## Installation Guide

If you have [Anaconda](https://www.anaconda.com/products/distribution) downloaded, then pandas, numpy, SQLAlchemy, and JupyterLab will be part of your package. You can check that they're ready to use by typing the following in your CLI terminal:
```python
conda list pandas
conda list jupyterlab
conda list numpy
conda list sqlalchemy
```
You'll need to install pyviz, hvplot, and geoviews:
```python
conda install -c pyviz hvplot geoviews
```
then you can check that these were installed by entering:
```python
conda list hvplot
conda list geoviews
```

---

## Usage

Open your CLI terminal and type
```python
jupyter lab
```
then JupyterLab will automatically open in your browswer. Use the left side menu bar to search for the `etf_analyzer.ipynb` file. Open this file. Then you can use the formaulas in the `.ipynb` file to analyze your database file(s) and gather the informaiton you need.

---

## Contributors

Rachel Ann Hodson, rachelannhodson@gmail.com

---

## License

MIT
