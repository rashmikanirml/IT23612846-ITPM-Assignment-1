# IT23612846-ITPM-Assignment-1
Playwright automation testing for Singlish to Sinhala transliteration
# IT23612846 - ITPM Assignment 1

Playwright automation testing for Singlish to Sinhala transliteration accuracy.

## Requirements

- Python 3.x
- pip

## Installation

Install dependencies:

pip install playwright openpyxl

Install Chromium browser:

python -m playwright install chromium

## How to Run

1. Make sure `Assignment 1 - Test cases.xlsx` and `test_automation.py` are in the same folder
2. Open Command Prompt and navigate to the folder
3. Run:

python test_automation.py

## What it does

- Opens the website: https://www.pixelssuite.com/chat-translator
- Types each Singlish input from the Excel file
- Captures the actual Sinhala output
- Saves results back into the Excel file automatically
