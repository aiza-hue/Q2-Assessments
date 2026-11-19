# Student Event Registration Formatter

## Description
This program cleans user-submitted student details and formats event deadlines clearly using built-in Python string methods and the datetime module.

## Language Used
Python 3

## String Features Used
- `strip()`: Removes extra leading and trailing whitespace from user inputs like names, emails, and student IDs.
- `title()`: Capitalizes the first letter of each word to standardize student names and event titles.
- `upper()`: Converts text to all uppercase letters for consistent formatting of student IDs, department codes, or course acronyms.

## Date/Time Features Used
- `datetime`: Parses, stores, and handles event registration dates and deadline timestamps.
- `strftime()`: Converts datetime objects into clean, human-readable strings (e.g., "November 19, 2026 at 01:50 PM") for confirmation messages.

## Version History
- Version 1: Initial version with basic user input collection and raw text output.
- Version 2: Added string cleaning and formatting methods (`strip()`, `title()`, and `upper()`) to standardize student records.
- Version 3: Integrated the `datetime` module and `strftime()` to validate and display formatted event deadlines.

• In my first version, my program could only let the user add and view basic text tasks in a single session.

• I improved my program by adding input formatting, due dates, and the ability to mark tasks as complete.

• The string method I used was .strip() and .lower() because I needed to clean up extra spaces and make user commands case-insensitive.

• The date/time feature I used was datetime.now() because I wanted to automatically record the exact timestamp when a task was created.

• The biggest change in my program was upgrading it from a simple list of strings to a structured task tracker that validates user input and tracks timestamps.
