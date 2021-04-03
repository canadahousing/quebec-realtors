# quebec-realtors
Data on Quebec realtors and disciplinary measures from [The Organisme d’autoréglementation du courtage immobilier du Québec](https://www.oaciq.com/en#find-broker)

Up to date as of March 9, 2021.

## Source
The [OACIQ](https://www.oaciq.com/en#find-broker) is the Authority of Real Estate Brokerages in Quebec. They host a database of realtors along with disciplinary measures. It is not possible to see or analyze the entire dataset and they make searching it difficult and slow.

## Data
The JSON and CSV files in this document contain 15,865 records. Brokerages are included but do not contain disciplinary mesaures. 

## Structure
| Field | Description |
| ------------- |:-------------|
| text | Text of the disciplinary measures section. Filter out fields that say "No administrative statement or disciplinary measure" to remove realtors with no issues. |
| html | Enter HTML contains of the disciplinary measures field. |
| name | Realtors name |
| dateCreated | Date scraped |
| url | Original URL |
| id | Realtor's ID |
| agencyId | ID of their real estate brokerage |
| agency | Brokerage name | 
| status | Realtor's satus, either valid or invalid |
