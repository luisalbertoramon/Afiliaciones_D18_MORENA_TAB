---
name: data-management
description: 'Manage and update the embedded JSON data for affiliations. Use for adding records, validating format, or exporting data.'
---

# Data Management for Affiliations

## When to Use
- Adding new affiliation records to the database
- Validating the format of the JSON data
- Exporting data for external use
- Cleaning or deduplicating records

## Procedures

### Adding Records
1. Extract current data from the HTML file's script tag
2. Parse the JSON array
3. Append new records in the format [name, date]
4. Ensure names are in uppercase and dates are valid
5. Update the script tag with the new JSON

### Validating Data
1. Check that data is a 2D array
2. Verify each record has exactly 2 elements: string and date
3. Ensure no duplicates based on name
4. Confirm dates are in a consistent format

### Exporting Data
1. Extract the JSON from the HTML
2. Optionally convert to CSV or other formats
3. Save to a separate file for backup or analysis