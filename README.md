# Fiscal Management

This Java project is developed for the OOP exam and serves as an application for managing people's incomes and expenses through a table-based interface.

## Features

-   Add, remove, and modify entries: Users can easily add, remove, and modify income and expense entries using the intuitive table interface.
-   Filter by date: The program allows users to filter data based on specific dates or date ranges, facilitating analysis and budget management.
-   Search by description: Users can search for entries by their description, enabling quick access to specific transactions.
-   Export to various formats: The application supports exporting budget data to Excel, TXT, and CSV formats, providing flexibility in data handling.
-   Save and load budgets: Users can save their budget in a file format specific to the program. This allows for easy storage and retrieval of budget data.
-   Auto-save feature: The program includes an auto-save feature, ensuring that users' budgets are periodically saved while the application is open.
-   Printing: The application provides printing functionality, allowing users to generate physical copies of their budget reports.

## Installation and Usage

Before downloading and using the program, ensure that Java JDK 19 or a higher version is installed on your system.

### macOS / Linux

1.  Open the terminal and navigate to the project directory.
2.  Check the permissions of the "run_unix.sh" file. If it doesn't have executable permissions, use the following command to grant them:
```bash
chmod +x run_unix.sh
```
3. Launch the "run_unix.sh" script. This script will compile the program, create an "out" directory, generate documentation in the "docs" directory, and finally, launch the program.
```bash
./run_unix.sh
```

### Windows
#### Option 1: Double-click

1. In the project directory, locate the "run_win.bat" file.
2. Double-click the "run_win.bat" file to execute it. This batch file performs similar actions to the "run_unix.sh" script.
> Note: If the program doesn't launch, or you encounter any issues, refer to Option 2 below.

#### Option 2: Command Prompt

1.  Open the command prompt (`cmd.exe`) and navigate to the project directory.
2.  Run the "run_win.bat" batch file. This batch file performs similar actions to the "run_unix.sh" script.
```
run_win.bat
```
Once the program is launched, you can start managing your incomes and expenses using the provided features. Remember to save your budget regularly, or rely on the auto-save feature to ensure data persistence. For detailed instructions on using the program's interface, refer to the generated documentation located in the "docs" directory.

## Documentation

The documentation for this project is automatically generated when running the program. The documentation file is located in the `docs` directory, specifically the `index.html` file. To access the documentation, open the `index.html` file in a common web browser application.
