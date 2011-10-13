# export.js 

export.js is a JavaScript utility that help transfer and download data to different formats, now it only exports to CSV  
format.  
 
## exportToCsv(data, keys) 
This function export csv formatted vertically to ease importing it to spreadsheet applications.

It expect two parameter the first is data which array of string arrays
example: 
var data = [ ["USA","France"], ["Washington DC", "Paris"] ] ; 
 
The second parameter is keys which expect array of strings that is associated with the data
example:  
var keys = ["Country","Capital"]; 

Calling exportToCsv(data, keys) the result will be :

Country,Capital
USA,Washington DC
France,Paris

if you import this csv to spreadsheet application, the data will look like this:

+---------+---------------+
| Country |    Capital    |
+---------+---------------+
| USA     | Washington DC |
| France  | Paris         |
+---------+---------------+
