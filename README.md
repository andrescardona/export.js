# export.js 

export.js is a JavaScript utility that help transfer and download data to different formats, now it only exports to CSV  
format. 

## exportToCsv(data, keys) 
This function export csv formatted vertically to ease importing it to spreadsheet applications.

It expect two parameter the first is data which array of string arrays, example: 

        var data = [ ["USA","France"], ["Washington DC", "Paris"] ] ; 
 
The second parameter is keys which expect array of strings that is associated with the data, example:

        var keys = ["Country","Capital"]; 

Calling <i>exportToCsv(data, keys)</i> the result will be :

Country,Capital <br />
USA,Washington DC <br />
France,Paris <br />

if you import this csv to spreadsheet application, the data will look like this:

<table border="1">
    <tr>
        <td>Country</td>
        <td>Capital</td> 
    </tr>
        <tr>
        <td>USA</td>
        <td>Washington DC</td> 
    </tr>
            <tr>
        <td>France</td>
        <td>Paris</td> 
    </tr>
</table>
