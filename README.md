# Cryptocurrency Investments
This application clusters cryptocurrencies by their performance in different time periods.  It then plots the data to visually show the performance of each cryptocurrency.
Specifically, the application uses the K-Means and PCA algorithms to analyze the crypto assets.

---


## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [csv](https://docs.python.org/3/library/csv.html) - For reading and writing to csv files

* [path](https://docs.python.org/3/library/pathlib.html) - Used to define file path

* [pandas](https://github.com/pandas-dev/pandas) - A flexible and power data analysis/manipulation Python library used in financial calculations.

* [scikit-learn](https://scikit-learn.org/) - A Python machine learning library that provides supervised and unsupervised learning algorithms.

* [hvplot](https://pyviz-dev.github.io/hvplot/user_guide/Introduction.html) - Provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
pip install -U scikit-learn
conda install -c pyviz hvplot
```

---

## Usage

To use the crypto arbitrage application you must first launch Jupyter Lab by executing the following command within Git Bash:

```python
jupyter lab
```

Within Jupyter Lab you should then be able to run and execute the following notebook:

``` python
crypto_investments.ipynb
```

---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/drew94591).

---

## License

Licensed under the MIT License. Copyright 2022 Drew Herrera.
