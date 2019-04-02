# PanglaoDB
This repo contains data and metadata from the database https://PanglaoDB.se

# *data* directory
## cell_type_abbrev.txt
Maps cell types to abbreviations.


| Column | Description
| ------------- |:-------------
| 1 | Cell type
| 2 | Abbreviation

## cell_type_annotations.txt
Mapping cell clusters to cell types.

| Column | Description
| ----------- |:----------
| 1 | SRA accession
| 2 | SRS accession
| 3 | Cluster index
| 4 | Cell type annotation
| 5 | P-value from Hypergeometric test
| 6 | Adjusted p-value (BH)
| 7 | Cell type Activity Score

## cell_type_annotations_markers.txt
Markers that were used to determine the cell type.

| Column | Description
| -------- |:---------
| 1 | SRA accession
| 2 | SRS accession
| 3 | Cluster index
| 4 | Gene symbol

## cell_type_desc.txt
Cell types and their descriptions.

| Column | Description
| -------- |:--------
| 1 | Cell type
| 2 | Biological description of this cell type
| 3 | Possible synonyms

## clusters_to_number_of_cells.txt
Clusters to number of cells

| Column | Description
| -------- |:--------
| 1 | SRA accession
| 2 | SRS accession
| 3 | Cluster index
| 4 | Number of cells

## cyclone.txt
Results from cell cycle analysis based on cyclone.

| Column | Description
| ------- |:----------
| 1 | SRA accession
| 2 | SRS accession
| 3 | Cluster index
| 4 | % cells in G1
| 5 | % cells in G2M
| 6 | % cells in S

# Reference
* Franzén,O., Gan,L.-M. and Björkegren,J.L.M. PanglaoDB: a web server for exploration of mouse and human single-cell RNA sequencing data. Database (2019) Vol. 2019: doi:10.1093/database/baz046
