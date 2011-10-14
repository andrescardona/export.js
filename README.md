# export.js 

export.js is a JavaScript utility that help transfer and download data to CSV format, other formats could be added later. 

#Demo
[Live demo](http://jsfiddle.net/YLyPL/) <br />
[export.js with Highchart](http://jsfiddle.net/b4caa/)

## exportToCsv(data, keys) 
This function exports to csv, formatted vertically to ease importing it to spreadsheet applications.

It expect two parameter the first is array of string arrays, example: 

        var data = [ ["USA","France"], ["Washington DC", "Paris"] ] ; 
 
The second is array of strings that is associated with the data, example:

        var keys = ["Country","Capital"]; 

Calling <i>exportToCsv(data, keys)</i> will create a csv that looks like this:

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

#Browser support
if you are using Chrome or Firefox the browser will download it as text file, if you are using IE a new window will pop up 
and then you could copy and paste the text or you could right click on the mouse and then save to a file.
