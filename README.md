# Excel Data Splitter

The Excel Data Splitter is a Python script designed to automate the process of dividing a large Excel dataset into multiple smaller Excel files. Each file is created based on the unique values found in a specified column of the dataset, facilitating the organization and analysis of data for research and development projects.

## How it works

The script reads the specified input Excel file, identifies unique values in the "Set Name" column, and then splits the data into multiple Excel files based on these unique values. Each resulting Excel file contains all rows from the input file that share the same "Set Name" value, preserving all data columns.

## Getting Started

These instructions will guide you through the setup and execution of the Excel Data Splitter script on your local machine.

### Prerequisites

Before running the script, ensure you have Python installed on your system. The script requires Python 3.x and the following Python libraries:

- pandas
- openpyxl (for .xlsx files)

To install Python, download the latest version from [python.org](https://www.python.org/) and follow the installation instructions.

### Installing

After installing Python, you can install the required libraries using pip. Open a command line interface (CLI) such as Command Prompt or PowerShell on Windows, and execute the following commands:

```bash
pip install pandas openpyxl

## Configuration

Before running the script, you need to specify the path to your input Excel file and the desired output directory in the script's configuration block.
```

