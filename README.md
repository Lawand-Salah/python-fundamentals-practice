# First Python Project

A collection of small, standalone Python scripts written while learning the basics of the language — console input/output, type conversion, string formatting, and simple arithmetic. Each file is an independent exercise rather than part of a single combined program.

## What's here

| Script | What it does |
|---|---|
| `PythonCar.py` | Takes a car's brand, model and colour, and prints a formatted summary |
| `academyScore.py` | Takes a name plus Maths and Science scores, and prints the total |
| `boxCalculation.py` | Calculates box volume from length, width and height |
| `dateOfBirth.py` | Builds a `DD/MM/YYYY` date-of-birth string from separate day/month/year inputs |
| `dollarConversion.py` | Converts pounds to dollars using a percentage-based exchange rate (e.g. enter `130` for a 1.30 rate), formatted to 2 decimal places |
| `examCalculation.py` | Takes 7 exam marks and prints the rounded average |
| `itemCalculation.py` | Calculates sale price and discount amount from a cost price and percentage discount |
| `markCalculation.py` | Averages 3 marks, formatted to 2 decimal places |
| `speedCalculation.py` | Calculates speed from distance travelled and time taken |
| `traingleCalculation.py` | Calculates the area of a triangle from its base and height |

## Getting started

Each script is run independently and prompts for input interactively:

```bash
python PythonCar.py
```

(or `python3`, depending on your system.)

## A repo housekeeping note

This repository has Visual Studio's local solution cache (`.vs/`) committed — files like `.suo`, `.wsuo` and `.vsidx` are IDE-specific, machine-local metadata, not project code, and were never meant to be shared. Adding a `.gitignore` entry for `.vs/` (and `git rm -r --cached .vs`) would keep the repo to just the 10 actual scripts.

## Notes

These are early learning exercises, so a few things are expected rather than bugs to fix: none of the scripts validate their input (entering text where a number is expected will crash with a `ValueError`), and `speedCalculation.py` will crash with a `ZeroDivisionError` if the time entered is `0`. Both are natural next steps once revisiting basic input validation (e.g. `try`/`except`, or checking for `0` before dividing) rather than issues with this version of the code.

## Author

Lawand Salah
