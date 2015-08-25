DATATABLES CHALLENGE:

Build a Data table with Datatables library (https://www.datatables.net/) and fill with some dummy data. Add excel like filtering possibility so that for each column we have a dropdown / overlay which allows us to filter the table on values found in the column. For this in the overlay we need a checkbox for each distinct value that was found in the column. By checking a checkbox, the table gets filtered immediately.

If we set filter on multiple columns, these should be additive. It is not necessary to solve the Task to 100 %. Important is to introduce an ovarall solvation.

TO RUN:

Unzip contents of folder onto a webserver location. No additional task is required.

COMPLETED:

All checkbox/filtering functionality:

- Defaults to show all
- Click on a filter - it filters automatically and unchecks the "Show All" option for that column
- Click on a filter again - it continues to build filter options based on regex data
- Unclick all filters or click on "Show All" - shows all items again for that field
- Fitlering capability is additive, across multiple columns.

TO DO:
(Remaining 10-20%)

- Move filter options from header to be within a pop-up / hidden div.
- Debug issues with special characters, such as ' $ ', which is currently causing the salary field to fail. Started work on index.html line 42.
