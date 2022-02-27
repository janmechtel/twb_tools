# calc_extractor
Parse a Tableau twb workbook file for calculations and parameters. 
Output a table of calculation names, formulas, and comments.
Also, generate a map of how the fields are related to one another.
 
# twb_translate
Upload a Tableau twb workbook file, and specify a source language and destination language, to get a translated version of the workbook.

# How to run

- `mkdir twb_tools`
- `cd twb_tools`
- `py -3 -m venv venv`
- `venv\Scripts\activate`
- `pip install Flask`
- `pip install googletrans`
- `pip install pandas`
- `$env:FLASK_APP = "app"`
- `flask run`