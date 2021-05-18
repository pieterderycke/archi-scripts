# archi-scripts
This respository contains a collection of jarchi utility scripts that should accelerate working with Archi on more complex Archimate models.

## LoadRelationshipsFromCsv
Load relationships between Archimate elements from a csv file. 
This script is based on the LoadCsv script of Steven Mileham. It requires PapaParse (https://www.papaparse.com/) to be available.

## CopyAttributesToClipboard
Copy a predefined set of attributes of the selected elements to the clipboard as a HTML table. This allows you to paste this table in applications such as Microsoft Word.
Please change the values of the variables "objectType" and "propertiesToExport" to match your own needs

```JavaScript
var objectType = "application-component"; // Change this to the Archimate element type that you whish to export

var propertiesToExport = [
    // Replace this with the list of Properties you which to export to the clipboard
];
```