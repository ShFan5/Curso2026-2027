# Hands-on assignment 3 – Self-assessment

## Deliverables

- [x] `openrefine/cleaning-operations.json` contains the cleaning operations applied to the source data.
- [x] `csv/200761-0-parques-jardines-csv-updated.csv` contains the cleaned CSV exported in UTF-8.
- [x] The updated CSV keeps the original 32-column schema and 208 park records.
- [x] The `PK` column was checked: all 208 records have a value and the 208 values are unique.

## Cleaning performed

- [x] Removed leading and trailing whitespace from cells.
- [x] Normalized repeated spaces and line breaks inside text fields.
- [x] Decoded HTML entities such as `&amp;` in descriptive fields.
- [x] Normalized common text-encoding artefacts where they could be repaired safely.
- [x] Kept identifiers, URLs, coordinates and postal codes as text so that their original values are not lost.
- [x] Removed no valid records; duplicate `PK` values were checked and none were found.

## Comments

The source dataset is the Madrid City Council parks and gardens CSV selected for Group 02. The cleaning is intentionally conservative: the original columns and values are preserved as much as possible, while whitespace, HTML entities and encoding issues are normalized before the RDF generation stage.
