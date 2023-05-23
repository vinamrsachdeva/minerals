# minerals

## Datasets

1. Coal rents: [COAL_RENTS.csv](https://github.com/vinamrsachdeva/minerals/blob/main/datasets/COAL_RENTS.csv)
2. Mineral rents: [MINERAL_RENTS.csv](https://github.com/vinamrsachdeva/minerals/blob/main/datasets/MINERAL_RENTS.csv)
3. Oil rents: [OIL_RENTS.csv](https://github.com/vinamrsachdeva/minerals/blob/main/datasets/OIL_RENTS.csv)
4. Natural gas rents: [NATGAS_RENTS.csv](https://github.com/vinamrsachdeva/minerals/blob/main/datasets/NATGAS_RENTS.csv)
5. Total mineral rents (coal, "minerals", oil, natural gas): [TOTAL_MINERAL_RENTS.csv](https://github.com/vinamrsachdeva/minerals/blob/main/datasets/TOTAL_MINERAL_RENTS.csv)

## Definitions
*Rent* here refers to resource rent, which is sale price minus costs (including a "reasonable" return on capital invested).

*Mineral rents* refers to the resource rents from mining copper, gold, iron ore, lead, nickle, silve, and zinc according to World Bank's "[The Changing Wealth of Nations 2021: Managing Assets for the Future](http://hdl.handle.net/10986/36400)" report but resource rents from mining tin, gold, lead, zinc, iron, copper, nickel, silver, bauxite, and phosphate according to [the page on their website](https://data.worldbank.org/indicator/NY.GDP.MINR.RT.ZS?end=2021&locations=IN&start=1970&view=chart) where the data has been taken from. Hence, [MINERAL_RENTS](https://github.com/vinamrsachdeva/minerals/blob/main/datasets/MINERAL_RENTS.csv) is the only dataset where there is some confusion; for the rest, World Bank's publications are consistent.

## Data sources
1. Coal rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.COAL.RT.ZS?locations=IN)
2. Mineral rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.MINR.RT.ZS?end=2021&locations=IN&start=1970&view=chart)
3. Oil rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.PETR.RT.ZS?locations=IN)
4. Natural gas rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.NGAS.RT.ZS?locations=IN)
5. GDP (current USD): [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=IN)
6. Official exchange rate (INR per USD): [World Bank](https://data.worldbank.org/indicator/PA.NUS.FCRF?locations=IN)
7. Population: [World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL?locations=IN)
8. Inflation, consumer prices (annual %): [World Bank](https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?locations=IN)

World Bank on the sources they used to estimate the rents in their report, "[The Changing Wealth of Nations 2021: Managing Assets for the Future](http://hdl.handle.net/10986/36400)":

![World Bank Sources](https://github.com/vinamrsachdeva/minerals/blob/main/wb_sources.png)
