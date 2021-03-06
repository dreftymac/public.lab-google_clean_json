# google_clean_json
> Transform google spreadsheet workbook into real-time, clean JSON

## Context
* google spreadsheet workbook (circa 2016-03)
* google apps script

## Problem
* Trevor has a google spreadsheet workbook with data on multiple worksheets;
* Trevor wants to get a real-time JSON representation of the workbook;
* Google supports JSON feed output format for a workbook, but the JSON is google_messy_json;
* Trevor wants to transform the google_messy_json into google_clean_json;

## Solution
* google_clean_json

## Pitfalls
* This approach requires making the google spreadsheet workbook *world readable*

## Credits
* [blog post source for google_clean_json.gs] (https://blogs.it.ox.ac.uk/acit-rs-team/2014/10/08/how-to-get-data-out-of-a-google-spreadsheet-using-jsonp/)

## See also
* https://github.com/dreftymac/public.lab-google-app-script
