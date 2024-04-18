# Home_Sales
## Module 22 Challenge

In this challenge, I used my knowledge of SparkSQL to determine key metrics about home sales data. Then I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

### Requirements
1. **A Spark DataFrame is created from the dataset.** (5 points)
2. **A temporary table of the original DataFrame is created.** (10 points)
3. **A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year.** (5 points)
4. **A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms for each year the home was built.** (5 points)
5. **A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year the home was built rounded to two decimal places.** (5 points)
6. **A query is written that returns the average price of a home per "view" rating having an average home price greater than or equal to $350,000, rounded to two decimal places.** (The output shows the run time for this query.) (10 points)
7. **A cache of the temporary "home_sales" table is created and validated.** (10 points)
8. **The query from step 6 is run on the cached temporary table, and the run time is computed.** (10 points)
9. **A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read.** (10 points)
10. **A temporary table of the parquet data is created.** (10 points)
11. **The query from step 6 is run on the parquet temporary table, and the run time is computed.** (10 points)
12. **The "home_sales" temporary table is uncached and verified.** (10 points)

### Reference articles:
- [Setting SPARK_HOME environment variable on Windows](https://stackoverflow.com/questions/38411914/the-spark-home-env-variable-is-set-but-jupyter-notebook-doesnt-see-it-windows)
- [Help Creating temporary views in Apache Spark SQL](https://docs.databricks.com/en/sql/language-manual/sql-ref-syntax-ddl-create-view.html)
- [What is Parquet file format?](https://www.databricks.com/glossary/what-is-parquet)

### Documentations:
- [Apache Spark Python API](https://spark.apache.org/docs/latest/api/python/index.html)
- [SparkSession API](https://spark.apache.org/docs/3.1.1/api/python/reference/api/pyspark.sql.SparkSession.html)
- [DataFrame API](https://spark.apache.org/docs/3.1.1/api/python/reference/api/pyspark.sql.DataFrame.html)
- [Creating temporary views](https://spark.apache.org/docs/latest/sql-ref-syntax-ddl-create-view.html)
- [Caching DataFrames in Spark SQL](https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/api/pyspark.sql.DataFrame.cache.html)
- [Parquet file format documentation](https://parquet.apache.org/docs/)
