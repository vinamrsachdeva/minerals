# natres

This repository contains data relevant to India's annual natural resource (coal, "minerals", oil, natural gas, forest) rents from 1971 to 2021 curated and estimated using several World Bank datasets. To understand how I estimated all values in the dataset, you can look at [this spreadsheet](https://docs.google.com/spreadsheets/d/1-Mwd9Yjtlltwksodfiiu61RiXPQXot29MHr7BBSr_Hk/).

{Forest to be added}

## Datasets

1. Coal rents: [COAL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/COAL_RENTS.csv)
2. Mineral rents: [MINERAL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/MINERAL_RENTS.csv)
3. Oil rents: [OIL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/OIL_RENTS.csv)
4. Natural gas rents: [NATGAS_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/NATGAS_RENTS.csv)
5. Total mineral rents (coal, "minerals", oil, natural gas): [TOTAL_MINERAL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/TOTAL_MINERAL_RENTS.csv)

## Definitions
*Rent or Resource rent*": sale price minus costs (including a "reasonable" return on capital invested).

*Mineral rent*: the resource rents from mining copper, gold, iron ore, lead, nickle, silve, and zinc according to World Bank's "[The Changing Wealth of Nations 2021: Managing Assets for the Future](http://hdl.handle.net/10986/36400)" report but resource rents from mining tin, gold, lead, zinc, iron, copper, nickel, silver, bauxite, and phosphate according to [the page on their website](https://data.worldbank.org/indicator/NY.GDP.MINR.RT.ZS?end=2021&locations=IN&start=1970&view=chart) where the data has been taken from. Hence, [MINERAL_RENTS](https://github.com/vinamrsachdeva/natres/blob/main/datasets/MINERAL_RENTS.csv) is the only dataset where there is some confusion; for the rest, World Bank's publications are consistent.

## Sources
1. Coal rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.COAL.RT.ZS?locations=IN)
2. Mineral rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.MINR.RT.ZS?end=2021&locations=IN&start=1970&view=chart)
3. Oil rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.PETR.RT.ZS?locations=IN)
4. Natural gas rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.NGAS.RT.ZS?locations=IN)
5. GDP (current USD): [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=IN)
6. Official exchange rate (INR per USD): [World Bank](https://data.worldbank.org/indicator/PA.NUS.FCRF?locations=IN)
7. Population: [World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL?locations=IN)
8. Inflation, consumer prices (annual %): [World Bank](https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?locations=IN)

World Bank on the sources they used to estimate the rents in their report, "[The Changing Wealth of Nations 2021: Managing Assets for the Future](http://hdl.handle.net/10986/36400)" (TABLE A.6 contains the revelant text):

![World Bank Sources](https://github.com/vinamrsachdeva/minerals/blob/main/wb_sources.png)
