# Finance Tracker

## Description

Finance Tracker is a simple application for tracking financial transactions. It allows you to add new transactions, view transactions over a specified period, and visualize the data in graphs.

## Features

- Add new transactions (income or expense)
- View transactions and summarize them by categories (income and expense) over a specified period
- Visualize income and expenses on a graph

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/finance-tracker.git
    ```
2. Navigate to the project directory:
    ```bash
    cd finance-tracker
    ```
3. Ensure you have all the necessary libraries installed. If not, install them using:
    ```bash
    pip install pandas matplotlib
    ```

## Usage

### Adding a Transaction

Choose option "1" to add a new transaction. You will be prompted to enter:
- The transaction date (format: `dd-mm-yyyy`)
- The amount
- The category ("I" for Income or "E" for Expense)
- Description (optional)

### Viewing Transactions

Choose option "2" to view transactions over a specific period. Specify:
- The start date (format: `dd-mm-yyyy`)
- The end date (format: `dd-mm-yyyy` or leave empty for the current date)

### Displaying a Graph

After viewing transactions, you will be prompted to display a graph. Choose "y" to show the income and expense graph.

## CSV File Format

The application uses the `finance_data.csv` file to store data. The file format is:
- `date` - Transaction date (format: `dd-mm-yyyy`)
- `amount` - Amount
- `category` - Category (income or expense)
- `description` - Description

## Requirements

- Python 3.x
- Pandas
- Matplotlib

## Author

Ulan Kurmanbekov

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
