# Big Data Challenge - Home Sales

## Objective
Use PySpark, SparkSQL and Google Colab to determine key metrics about home sales data provided.

## Process
Spark is utilized to create temporary views, partition the data, cache and uncache a temporary table. 

## Questions to answer

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
<img width="170" alt="Screenshot 2023-09-29 at 11 31 41 AM" src="https://github.com/javsgon/Home_Sales/assets/125521896/a2c4c682-32af-4270-852a-8262ad928392">

- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
<img width="204" alt="Screenshot 2023-09-29 at 11 31 50 AM" src="https://github.com/javsgon/Home_Sales/assets/125521896/f45581bc-334a-45b6-90ad-d29b61a02340">

- What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
<img width="204" alt="Screenshot 2023-09-29 at 11 32 00 AM" src="https://github.com/javsgon/Home_Sales/assets/125521896/79ab5d9e-9cf4-4bde-aa9d-b18883d30df0">

- What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
<img width="293" alt="Screenshot 2023-09-29 at 11 32 17 AM" src="https://github.com/javsgon/Home_Sales/assets/125521896/a51e7c66-f925-405e-b6c1-23aa9cb8f30b">

- Cache your temporary table. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
<img width="281" alt="Screenshot 2023-09-29 at 11 32 26 AM" src="https://github.com/javsgon/Home_Sales/assets/125521896/9bcc8d4e-27b4-4fab-9555-485c91367bf9">

- Partition by the "date_built" field on the formatted parquet home sales data. Create a temporary table for the parquet data. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
<img width="290" alt="Screenshot 2023-09-29 at 11 32 37 AM" src="https://github.com/javsgon/Home_Sales/assets/125521896/f0e4cc56-6d1c-442e-9744-ddf3e77166ab">

