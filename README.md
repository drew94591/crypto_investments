# Cryptocurrency Investments
This application identifies if there are any potential profit opportunities between two bitcoin exchanges via arbitrage. Arbitrage occurs when the price of one exchange is much lower than
another exchange such that you could buy in this case bitcoin at the lower priced exchange and then selling at the higher exchange for a profit minus any exchange fees. 
In this case, the two exchanges are Bitstamp and Coinbase. Their bitcoin prices for the first part of 2018 has been provided.  A profit is made if the spread between the two exchanges
is greater than 1% to cover the costs of doing the transaction.  This application then displays the calculated returns on each qualifying arbitrage.

---

## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [csv](https://docs.python.org/3/library/csv.html) - For reading and writing to csv files

* [path](https://docs.python.org/3/library/pathlib.html) - Used to define file path

* [pandas](https://github.com/pandas-dev/pandas) - A flexible and power data analysis/manipulation Python library used in financial calculations.

* [matplotlib](https://matplotlib.org) - A comprehensive library for creating static, animated, and interactive visualizations in Python.

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
