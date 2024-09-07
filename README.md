# Excel Price Correction Script

This is a Python script that processes an Excel file, applies a 10% correction to a price column, and adds the corrected prices to a new column in the Excel sheet. The script then generates a bar chart for the corrected prices and adds it to the sheet.

## Features
- Reads an Excel file.
- Applies a 10% discount to the values in the third column.
- Writes the corrected values to a new column.
- Creates a bar chart displaying the corrected prices.
- Saves the modified Excel file.

## Requirements
This script requires Python and the following libraries:
- `openpyxl`

You can install the required library using pip:
```bash
pip install openpyxl


## Usage

1. Clone the repository using the following command:

```bash
git clone https://github.com/thabir303/automation-with-python.git
```
2. Navigate to the directory:

```bash
cd automation-with-python
```

3. Make sure you have an Excel file with at least 3 columns. The script applies the correction to the values in the third column (prices).

4. Run the script by passing the filename of your Excel file when prompted:

```bash
python automation.py
```
5. Example:
```bash
> filename : your_excel_file.xlsx
```
