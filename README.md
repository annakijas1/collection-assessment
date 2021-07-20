# Collection Assessment
 Data for assessing diversity of music score collection at Lilly Music Library, Tufts University

# About this repository
This repository contains the following files:
* composers-v2021-06-29-current.twbx
* fy21-composers.csv
* fy21-scores.csv
* scores-birthyear.rawgraphs

The Tableau workbook, [composers-v2021-06-29-current.twbx](https://github.com/annakijas1/collection-assessment/blob/main/composers-v2021-06-29-current.twbx), uses data from the [fy21-composers.csv file](https://github.com/annakijas1/collection-assessment/blob/main/fy21-composers.csv) to create a tree map visualization of the 189 composers whose works were added to the music library's collection in FY2020-21.

The visualizations created from this data can be viewed on the [Lilly Music Library Collection LibGuide](https://researchguides.library.tufts.edu/lillymusiclibrary-collection). 

Additional details about each score, including a link to the library catalog record are available at [https://bit.ly/scores2020-21](https://bit.ly/scores2020-21).

## About the Data Sources
Lilly Music Library collections data was exported via the analytics reporting process in Alma. MMS-IDs were used to pull and match Primo links with individual titles using a Python script. The data was cleaned using OpenRefine.

### Composer data
Demographic details about each composer were identified and added to the collection data, because this type of data is not available in library catalog records. Racial/ethnicity, gender-identity, and nationality data was reviewed from a variety of sources, including:

* [DBpedia](https://www.dbpedia.org/)
* [Wikipedia](https://www.wikipedia.org/)
* Library of Congress [Linked Data Service](https://id.loc.gov/)
* [VIAF](https://viaf.org/)
* Grove Music Online (Oxford)
* Individual composer websites
* Publisher websites

Data on this site is released under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
