# Analyzing-CIA-Factbook-Data-Using-SQLite-and-Python
In this project, I worked with data from the CIA World Factbook, a compendium of statistics about all of the countries on Earth. The Factbook contains demographic information like:

population - The population as of 2015.

population_growth - The annual population growth rate, as a percentage.

area - The total land and water area.

You can download the SQLite database, factbook.db,[from this GitHub repo](https://github.com/factbook/factbook.sql/releases) if you want to work with it on your own computer. In this project, we'll explore the Python SQLite workflow to explore, analyze, and visualize data from this database. First things first, let's get familiar with the database.
Here are the descriptions for some of the columns:

name - The name of the country.
area - The total land and sea area of the country.
population - The country's population.
population_growth- The country's population growth as a percentage.
birth_rate - The country's birth rate, or the number of births a year per 1,000 people.
death_rate - The country's death rate, or the number of death a year per 1,000 people.
area- The country's total area (both land and water).
area_land - The country's land area in square kilometers.
area_water - The country's waterarea in square kilometers.

