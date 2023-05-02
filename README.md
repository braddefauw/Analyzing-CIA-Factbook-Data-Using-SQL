# Analyzing-CIA-Factbook-Data-Using-SQL

In this project, we'll work with data from the [CIA World Factbook](https://www.cia.gov/the-world-factbook/), a compendium of statistics about all of the countries on Earth. The Factbook contains demographic information like the following:

* `population` — the global population.
* `population_growth` — the annual population growth rate, as a percentage.
* `area` — the total land and water area.

In this project, we'll use SQL in Jupyter Notebook to analyze data from this database. 

We'll use the following code to connect our Jupyter Notebook to our database file:

```
%%capture
%load_ext sql
%sql sqlite:///factbook.db
```
