# Python Expense Tracker

A simple command-line app for tracking your spending. Expenses are saved to `expenses.json`.

## Project structure

```
├── tracker.py       # the expense tracker app
├── expenses.json    # where your expenses are saved
├── file.py          # Git practice file (not part of the app)
└── README.md
```

## Requirements

Python 3.8 or newer. No extra packages needed.

## Usage

```bash
python tracker.py add 12.50 food "Lunch at the cafe"   # add an expense
python tracker.py list                                 # show all expenses
python tracker.py total                                # show total spent
python tracker.py delete 1                             # delete expense #1
```

To change the currency symbol (default is `$`):

```bash
TRACKER_CURRENCY="£" python tracker.py list
```
