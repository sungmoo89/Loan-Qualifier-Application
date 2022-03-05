# Loan Qualifier Application

This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

1. Upon launching the loan qualifier application you will be first asked to find the path for data.
![How to load data](./data/Image/how_to_load_data.png)
2. Punch in the data of yours to get the right data.
![How to provide information](./data/Image/how_to_provide_information.png)
3. This shows how you can save the data. You can set your .csv file name to anything you like
![How to save result to .csv](./data/Image/save_to_csv.png)

---

## Contributors

Sungmoo Ban

---

## License

Sungmoo Ban