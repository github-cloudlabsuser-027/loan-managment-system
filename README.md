# Loan Management System

This is a comprehensive loan management system designed to streamline the process of managing customer information and loan data. It offers a suite of functionalities for determining customer eligibility, managing loan repayments, and executing various loan management operations efficiently.

## Project Structure

The project is organized as follows:

```
loan_management_system
├── data
│   ├── customers.csv
│   └── loans.csv
├── src
│   ├── __pycache__
│   ├── customer.py
│   ├── eligibility.py
│   ├── loan.py
│   ├── repayment.py
│   └── utils.py
├── tests
│   └── customer_test_cases.py
├── loan_application_ui.py
├── main.py
├── python_coding_standards.json
└── README.md
```

## Files Overview

- [`data/customers.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fdata%2Fcustomers.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\data\customers.csv"): Contains customer data for the loan management system, including names, addresses, and contact details.

- [`data/loans.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fdata%2Floans.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\data\loans.csv"): Stores loan data, such as loan amounts, interest rates, and repayment schedules.

- [`src/customer.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fsrc%2Fcustomer.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\src\customer.py"): Defines the `Customer` class, representing a customer with properties like name, address, and methods for data retrieval and updates.

- [`src/loan.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fsrc%2Floan.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\src\loan.py"): Defines the [`Loan`](command:_github.copilot.openSymbolFromReferences?%5B%7B%22%24mid%22%3A1%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%7B%22line%22%3A0%2C%22character%22%3A0%7D%5D "README.md") class, representing a loan with properties such as amount, interest rate, and methods for interest calculation and payment management.

- [`src/eligibility.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fsrc%2Feligibility.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\src\eligibility.py"): Contains functions to assess a customer's eligibility for a loan based on credit scores, income levels, and other criteria.

- [`src/repayment.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fsrc%2Frepayment.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\src\repayment.py"): Includes functions for loan repayment management, such as calculating monthly payments, generating repayment schedules, and handling late payments.

- [`src/utils.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fsrc%2Futils.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\src\utils.py"): Provides utility functions for CSV file operations, date formatting, and other common tasks across the loan management system.

- [`main.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\main.py"): The entry point of the system, facilitating user interaction, data management, and execution of loan management operations.

## Getting Started

To effectively use the loan management system, follow these steps:

1. Populate [`data/customers.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fdata%2Fcustomers.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\data\customers.csv") and [`data/loans.csv`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fdata%2Floans.csv%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\data\loans.csv") with the necessary customer and loan data, respectively.

2. Execute [`main.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fa.kailas.patil%2FOneDrive%20-%20Accenture%2FDesktop%2FLoan_management_system%2Floan_management_system%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\a.kailas.patil\OneDrive - Accenture\Desktop\Loan_management_system\loan_management_system\main.py") to launch the system.

3. Adhere to the system's prompts and instructions to carry out various operations, such as verifying customer eligibility, managing loan repayments, etc.

4. For detailed insights into the system's functionalities and implementation, consult the source code documentation and comments.

**Note:** This system is designed for demonstration purposes and may lack certain features and validations needed for a production environment.

## Contributing

Contributions to improve the loan management system are welcome. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes with clear, descriptive messages.
4. Push your branch and submit a pull request.

For major changes, please open an issue first to discuss what you would like to change. Ensure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)