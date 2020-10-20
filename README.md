# Nobel Prize Data Analysis With Power BI
### Visualization about the Nobel Prizes and the Nobel Prize Laureates

For this project, I've used the Rest based API provided by [Nobelprize.org](https://www.nobelprize.org). The Site offers open data to developers in two ways: as API and as Linked Data. The data is free to use and it contains information about the Nobel Prizes and the Nobel Laureates. The data is updated as the information on www.nobelprize.org is updated, including at the time of announcements of new Laureates.

Endpoints for the API are:
https://api.nobelprize.org/2.0/laureates
This endpoint sorts the output based on Nobel Laureates (persons and/or organizations). It returns all information about Laureates and Nobel Prizes.
https://api.nobelprize.org/2.0/nobelPrizes
This endpoint sorts the output based on Nobel Prizes. Upon request, this endpoint returns a shorter result and the Laureates endpoint needs to be called as well to get the full response.

