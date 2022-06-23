# Staatskalender: the Swiss Federal Directoy
## An always up-to-date dump of the federal directory website

The website [www.staatskalender.admin.ch](https://www.staatskalender.admin.ch) is the official the official directory for the entire Swiss Confederation[^1]: Federal Assembly, Federal Administration and Tribunals[^2]. 

The site allows one to explore most of the organisation chart of the Swiss Confederation, it presents some personal data (e.g. head of units). Typically when searching for the names of federal offices, their hierarchical structure, abbreviations and names in official languages one has to consult this site. 


[^1]: Staatskalender, Annuaire fédéral, Annuario federale.
[^2]: Assemblea federale, Consiglio federale e Amministrazione federale, Tribunali federali e forze dell'ordine, Assemblée fédérale, Conseil fédéral et administration fédérale, Tribunaux fédéraux et services répressifs, Bundesversammlung, Bundesrat und Bundesverwaltung, Gerichte und Strafverfolgungsbehörden des Bundes.

## Changes with respect to the original data
- Data is provided _as is_, objects are updated at least once a month. 
- In order to keep directories reasonably small, objects file names use the following notation ``/#{product}/#{id[0..4]}/#{id}.json``
- Files are stored according to their URI's path with the ``.json`` extension.
- ``JSON`` objects are prettified in order to take advantage of git to track changes.

## Additional files
CSV files are automatically generated with identifiers, names, abbreviations in the three official languages and English: 
- (depth 2) departments: ```government_depth2_departments.csv```
- (depth 3) departments and offices ```government_depth3_offices.csv```
- (detph 4) departments, offices and main units ```government_depth4_main_units.csv```
- (depth 13) all published structure ```government_depth13_all_units.csv```

## Feedbacks
Feedbacks are welcome. For suggestions, missing or incorrect data open an issue.

## Resources
- [www.staatskalender.admin.ch](https://www.staatskalender.admin.ch), where the data is officialy presented.

## Licence
Swiss Federal Chancellery requirements for the use of the data are summarized [here](https://www.admin.ch/gov/en/start/terms-and-conditions.html). This repository is licensed under the [CC BY-NC-SA 4.0 licence](https://creativecommons.org/licenses/by-nc-sa/4.0/) and cannot be used for commercial purposes. 

Droid Factory.
