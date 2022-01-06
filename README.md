# Convert CSV File TO String Excel XLSX

## Context
- Facebook is using 64 bit ID, which is out of support for normal excel file.
- Since we are using excel to read their CSV file, those ID will be automatically convert to number, and since it's out of support range number, the real ID will be cut for last few digits.
- To resolve this issue, running this script to convert all CSV file to Excel XLSX file, and convert all the fields to Text format (String)
- This will help to maintain the ID.

## How to run
1. Better to use visualstudio code to escape from some technical part (handling virtual env for python and running shell command)
2. Pre-install Python
3. Create `/input` folder and `/output` folder
4. Put all `.csv` file in `input` folder
5. Run `index.py`
6. Result will be in `output` folder