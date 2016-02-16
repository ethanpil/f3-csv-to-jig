# f3-csv-to-jig

## Intro
This tool is designed to easily create simple Jig databases from CSV files. If you don't know what a JIG database is then you probably dont use the Fat Free Framework (http://fatfreeframework.com/).

I have included some sample data for USA states to show you how it works and what the output will be.

## Usage
* Fill the left side textarea with CSV data. One row per line.
* Set the first row to the key names, and then all subsequent rows will be encoded into the JIG JSON format. 
* Fields do not need to be enclosed in "double quotes" unless they contain special characters or commas.
* You can save the downloaded file and load it into JIG as a JSON database.
* 
### Warning
* Currently (and probably forever) **this tool only supports simple rows of JSON data**  (no serialzed or complex data).
