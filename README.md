# Number of cities per country

## Created by Patrycja Decowska
## Data source Sample database from SQL course

## Main Goal 
To present the number of cities for each country in a given database.

## Description
This project analyzes how many cities exist in each country using data
from a fictional SQL database.

### SQL
The country table is insufficient to store all of the information I need.
My query required data from two tables country table and city table.
What is more, I have used aggregate function `COUNT` to count the number
of cities.

`INNER JOIN` allows me to select data from two tables and `country_id` is
the common field in both of them. Then I used `GROUP BY` in my code to take
duplicate values and collect them together. `HAVING` clause allows me to
filter the results. Thanks to this, I am able to see total number of
cities for each country.

At the end of my code I used `ORDER BY` to sort in descending order by
number of cities and in ascending alphabetical order for countries.

**SQL clauses used in the code:** 
- `SELECT`
- `COUNT`
- `INNER JOIN`
- `GROUP BY`
- `HAVING`
- `ORDER BY`

### Python
I have imported `pandas` and `matplotlib` libraries and uploaded the dataset
using `pd.read_csv`. I explored basic information, checked structure and
statistics. Afterwards, I created a bar chart to visualize the number of
cities per country.

## Results

The chart shows that India has the most cities in this database.
Moreover, Netherlands, Pakistan, Saudi Arabia, South Korea and Spain
have the lowest number of cities. - All of them have the same number of
cities.
