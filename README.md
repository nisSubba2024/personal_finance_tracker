# Command-Line Personal Finance Manager

A command-line tool for managing personal finances. This project provides functionalities to add, modify, delete transactions, view logs, generate reports, and visualize financial data. It uses Python with pandas for data manipulation, matplotlib for plotting, and includes a logging system to track changes and errors.

When trying out the application, you can delete the CSV files or keep it.

## Features

- **Add Transactions**: Easily add new transactions with details including date, amount, category, and description.
- **Modify Transactions**: Update existing transactions with new details.
- **Delete Transactions**: Remove transactions from the records.
- **View Logs**: Access logs for transactions, new entries, updates, and deletions.
- **Summary Reporting**: View a summary of income and expenses, including total amounts and average transactions.
- **Income/Expense Breakdown**: Generate detailed reports of income and expenses by description.
- **Visualization**: Plot graphs to visualize income and expenses over time.
- **Documentation**: Documented with Doxygen for detailed code description.

## Documentation
You can access the detailed documentation for the project [here](https://nissubba2024.github.io/personal_finance_tracker/annotated.html).

## Technologies Used

- **Programming Languages**: Python
- **Data Analysis**: pandas
- **Data Visualization**: matplotlib
- **File Handling**: CSV
- **Command-Line Interface**: Custom menus and prompts

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/nisSubba2024/personal_finance_tracker.git
    cd personal_finance_tracker
    ```

2. Create Virtual Environment
```bash
python3 -m venv .venv
```

3. Activate Virtual Environment
```bash
source .venv/bin/activate
```
4. Install requirements libraries
```bash
pip3 install -r requirements.txt
```

## Usage

1. **Run the Program**: Execute the `run.py` script to start the program.
    ```bash
    python3 run.py
    ```

2. **Add a New Transaction**:
    - Select option `1` from the main menu.
    - Provide the required details such as date, amount, category, and description.

3. **Modify a Transaction**:
    - Select option `3` from the main menu.
    - Choose the field to modify and provide new values.

4. **Delete a Transaction**:
    - Select option `4` from the main menu.
    - Confirm the transaction ID to be deleted.

5. **View Logs**:
    - Select option `5` from the main menu.
    - Choose which log to view (Transactions Log, New Entry Log, Update Log, Delete Log).

6. **View Summary Balance**:
    - Select option `6` from the main menu.
    - View a summary of total income, total expenses, and net savings.

7. **View Income/Expense Report**:
    - Select option `7` from the main menu.
    - Choose to view either the Income Report or Expense Report.

8. **Exit**:
    - Select option `8` from the main menu to exit the program.

## File Descriptions

- **`run.py`**: Main file to run the program.
- **`ascii_art.py`**: Contains ASCII art for title of the program.
- **`user_entry_manager.py`**: Manages user inputs and validation.
- **`csv_manager.py`**: Handles CSV file operations and data manipulation.
- **`update_log_manager.py`**: Manages logging of transaction updates, deletions, and other modifications.
- **`report_manager.py`**: Generates and displays reports and visualizations.

