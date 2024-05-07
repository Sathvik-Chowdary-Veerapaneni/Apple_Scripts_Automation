# Numbers Sheet Duplication Script

This AppleScript is designed to automate the process of duplicating a template sheet in a Numbers spreadsheet for each day of a month. The script works by copying the contents of a specified template sheet and pasting them into a new sheet for each day of the month.

## Prerequisites

- Apple's Numbers application
- A Numbers spreadsheet with a template sheet that you want to duplicate

## Important Notes

- **Do not interrupt the script**: Once the script starts running, do not use your keyboard or mouse until the script has finished. Interrupting the script may cause it to not work correctly.

- **Save your work**: Always save your work before running the script. The script makes significant changes to your Numbers document, so it's important to have a saved version of your work in case anything goes wrong.

- **Check the results**: After the script has finished running, check the new sheets in your Numbers document to make sure the contents have been copied correctly.

- **Close other Numbers documents**: Make sure to close any other open Numbers documents before running the script. Having other documents open may interfere with the script.

## Steps to Use the Script

1. **Open your Numbers spreadsheet**: The spreadsheet should contain the template sheet that you want to duplicate.

2. **Set up the AppleScript**: Open the AppleScript Editor on your Mac and paste the provided script into a new document.

3. **Customize the script**: Replace `"June_2024"` with the name of your Numbers spreadsheet and `"June 1, 2024"` with the name of your template sheet. Set the `numDays` variable to the number of days in the month.

4. **Run the script**: Click the Run button in the AppleScript Editor to run the script. The script will create a new sheet for each day of the month, duplicating the contents of the template sheet.



