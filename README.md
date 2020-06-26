# Excel-Dynamic-Drop-Down-List
Guide on creating a self updating list for the Data Validation drop down list in Excel.

1. The first step is to create your list.
2. Turn list into a table.
3. Name the table and column. (Optional: hide header and format column)
4. Select cell where you want the dropdown to be and apply Data Validation.
5. In the Validation criteria, select "List" in the drop down for 'Allow'.
6. In the source use the following formula ```=INDIRECT("tableName[columnName]")```
7. Click OK.

Now you will have a drop down which you can select the items from.

To update the drop down, simply append to the list item to the bottom of the table.

