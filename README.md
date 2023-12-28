# LineCalculations
JavaScript was used to make tables out of an excel spreadsheet, allowing for easy viewing and altering of the information so that calculation may be done faster. Previously, performing these calculations took time as many of the workers entering the data would make errors in typing, making the calculations shift or invalid.

## Loading

Use the "Choose File" buttons to select the excel file for the line filler data. Each line's data needs to go to its appropriate line so that it matches to its calculations.<br>

Notice that when the data is loaded, it fills in the empty box as shown in the image below. It does not load data if there is no "Null Category #1" or Null Category #4" information, but skips it instead. This because these data are essential and can not be implied by the data surround it. In addition, if there is something not in a mm/dd/yyyy format within the date column, the load will overwrite this value with the previous value as an estimation, the same with the "intials" and "shift" columns (This can be seen in the images below).  This will not work if the first row in the "Date" column is not in the mm/dd/yyyy format.

**Notes:** <br>
* This program is designed for a specific layout on excel which will work if the worksheet’s layout is not altered to the eamples given. The data itself may be altered.
* Reselecting the same file will not update the table; however, selecting a different file will update the table.



## Sorting

## Deleting Rows

## Filtering

## Changing Table Values

## Calculating
