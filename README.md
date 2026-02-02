Question 2
    - What is the rendered value of the variable file when the inputs taxi is set to green, year is set to 2020, and month is set to 04 during execution? (1 point)

    - Substituting values in "{{inputs.taxi}}_tripdata_{{trigger.date | date('yyyy-MM')}}.csv"

    - OUTPUT: green_tripdata_2020-04.csv


Question 3
    - How many rows are there for the Yellow Taxi data for all CSV files in the year 2020?

    - select COUNT(*) from yellow_tripdata where filename ilike 'yellow_tripdata_2020-%';

    - OUTPUT: 24648499


Question 4
    - How many rows are there for the Green Taxi data for all CSV files in the year 2020?

    - select COUNT(*) from green_tripdata where filename ilike 'green_tripdata_2020-%';

    - OUTPUT: 1734051


Question 5
    - How many rows are there for the Yellow Taxi data for the March 2021 CSV file?

    - select COUNT(*) from yellow_tripdata where filename = 'yellow_tripdata_2021-03.csv';

    - OUTPUT: 1925152

