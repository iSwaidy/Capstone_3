# capstone 3: sales analysis with power bi

a power bi report analyzing four years of sales for emporium, a virtual student bookstore. the regional director asked for a look at sales trends and key insights for the south region sales team.

## region

south region, covering florida, south carolina, and texas.

## data

the analysis combines store and online sales from 2022 through 2025, around 71,000 transactions in total. it also pulls in the product catalog, store locations, and a separate book list with author names for general books.

source files: `Capstone3_Sample_Sales.xlsx` and `book_list.txt`.

## the report

`Ramirez_capstone3.pbix` has two pages with four core visuals.

page 1, booming business with a plot twist:
- a line chart showing the sales trend from 2022 to 2025
- a column chart breaking sales down by category

page 2, where we sell and what they read:
- a donut chart showing sales by state
- a table of the top 10 books with their authors, covering general books and excluding textbooks

## key findings

sales grew 180% over the four years, reaching $15.8 million. technology drives about 73% of revenue, while general books make up just 3%. texas alone accounts for more than half the region's sales at 53%, with south carolina under 9%. online and in store sales come out nearly even, close to a 50/50 split.

## how it was built

the data was cleaned and shaped in power query. that meant standardizing state names, fixing the category fields, building proper dates, and combining store and online records into one sales table. the model uses a star schema, with the sales table related to products, a date table, and a book list lookup that supplies the author names. the whole model is filtered down to the south region.

## tools

power bi desktop

## video

10 minute walkthrough:
