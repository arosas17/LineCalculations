# LineCalculations
JavaScript was used to make tables out of an excel spreadsheet, allowing for easy viewing and altering of the information so that calculation may be done faster. Previously, performing these calculations took time as many of the workers entering the data would make errors in typing, making the calculations shift or invalid.

## Loading

Use the "Choose File" buttons to select the excel file for the line filler data. Each line's data needs to go to its appropriate line so that it matches to its calculations.<br>

Notice that when the data is loaded, it fills in the empty box as shown in the image below. It does not load data if there is no "Null Category #1" or Null Category #4" information, but skips it instead. This because these data are essential and can not be implied by the data surround it. In addition, if there is something not in a mm/dd/yyyy format within the date column, the load will overwrite this value with the previous value as an estimation, the same with the "intials" and "shift" columns (This can be seen in the images below).  This will not work if the first row in the "Date" column is not in the mm/dd/yyyy format.

**Notes:** <br>
* This program is designed for a specific layout on excel which will work if the worksheet’s layout is not altered to the eamples given. The data itself may be altered.
* Reselecting the same file will not update the table; however, selecting a different file will update the table.



## Sorting

Click on the headers to sort the data depending on the header clicked (ascending order). Clicking on the header again after sorting will bring it to descending order. Use this to find unrealistic data or outliers that need to be removed or changed.
<br>

If the “Null Category #3” header is selected, any blank spaces will appear at the top. This makes it easier to locate data that either needs the row deleted or the missing value filled in. A similar function is placed on the “Null Category #5” header where, if sorted, all empty boxes are placed toward the bottom for easy data viewing.  

## Deleting Rows

If a row needs to be deleted, click on the row and it will highlight red, as shown below. Choose multiple rows from across the different tables and click the “Delete Rows” button on the left. The row will then be deleted.

**WARNING:** This data is not permanently deleted. It will return if the “Filter” button is used and the date matches the selected criteria of month and year.

## Filtering

## Changing Table Values

## Calculating
