---
description: "Update the embedded JSON data in the HTML file with new affiliation records"
argument-hint: "Provide the new data as a list of [name, date] pairs"
---

Update the embedded JSON data in the HTML file with the provided new affiliation records.

Steps:
1. Read the current data from the script tag with id="dbData"
2. Append or replace the data with the new records
3. Ensure the data is a valid 2D array [[name, date], ...]
4. Update the HTML file with the new JSON

New records: {{input}}