# Lesson lab notebooks

Runnable versions of the Learning Hub lesson labs. They are generated from the lessons
(`databricks-learning-hub/scripts/build_lab_notebooks.py`), so do not edit them by hand:
change the lesson, then regenerate.

## Run in Databricks Free Edition (recommended)

1. **First time only:** sign up at <https://login.databricks.com/?intent=CE_SIGN_UP>.
   Choose *Continue with Google*, *Continue with Microsoft*, or enter your email and type
   the 6-digit code Databricks emails you. Your workspace is created for you.
2. Copy the **raw** link of a notebook below.
3. In Databricks, open **Workspace**, then **⋮ → Import**, choose **URL**, paste the link and
   click **Import**. (Or download the file and import it as a file.)
4. Attach **Serverless** compute and run the cells from top to bottom.

The Data Analyst labs (SQL warehouses to Genie) also have steps in the SQL editor, dashboards
and Genie. Those steps are written as text cells; follow them in the Databricks interface.

## Run in Google Colab

Notebooks in [`colab/`](colab) open with one click from the lesson page
(`https://colab.research.google.com/github/<owner>/<repo>/blob/<branch>/notebooks/colab/<lesson>.ipynb`).
They cover plain Python and open-source Spark only; the PySpark notebook installs PySpark
(and Java if it is missing) in its first cell.

## Notebooks

| Lesson | Databricks | Colab |
| --- | --- | --- |
| What is Databricks? The platform, your data and a first tour | [databricks-intro](databricks/databricks-intro.ipynb) | |
| Tables and rows: CREATE, INSERT, UPDATE and DELETE | [sql-tables-crud](databricks/sql-tables-crud.ipynb) | |
| SQL basics: SELECT, WHERE, ORDER BY and LIMIT | [sql-select-basics](databricks/sql-select-basics.ipynb) | |
| Data types and functions: CAST, text, numbers and dates | [sql-functions-types](databricks/sql-functions-types.ipynb) | |
| NULLs and CASE | [sql-nulls-case](databricks/sql-nulls-case.ipynb) | |
| Aggregation: GROUP BY, HAVING and counting correctly | [sql-aggregation](databricks/sql-aggregation.ipynb) | |
| SQL joins: inner, left, anti and semi | [sql-joins](databricks/sql-joins.ipynb) | |
| CTEs and subqueries | [sql-ctes-subqueries](databricks/sql-ctes-subqueries.ipynb) | |
| Window functions | [sql-window-functions](databricks/sql-window-functions.ipynb) | |
| Views and safe writes: CTAS, overwrite, MERGE and history | [sql-tables-writes](databricks/sql-tables-writes.ipynb) | |
| Python basics: values, strings, lists and dictionaries | [py-values-collections](databricks/py-values-collections.ipynb) | [colab](colab/py-values-collections.ipynb) |
| Python: loops, conditions and functions | [py-control-functions](databricks/py-control-functions.ipynb) | [colab](colab/py-control-functions.ipynb) |
| Working with records | [py-records](databricks/py-records.ipynb) | [colab](colab/py-records.ipynb) |
| Errors and validation | [py-errors-validation](databricks/py-errors-validation.ipynb) | [colab](colab/py-errors-validation.ipynb) |
| Python in Databricks notebooks | [py-databricks-notebooks](databricks/py-databricks-notebooks.ipynb) | |
| Your first DataFrame (PySpark) | [pyspark-first-dataframe](databricks/pyspark-first-dataframe.ipynb) | [colab](colab/pyspark-first-dataframe.ipynb) |
| Databricks SQL and SQL warehouses | [dbsql-warehouses](databricks/dbsql-warehouses.ipynb) | |
| Analyzing queries: query history, query profile and caching | [query-performance](databricks/query-performance.ipynb) | |
| Getting data in: uploads, volumes, read_files and COPY INTO | [analyst-data-import](databricks/analyst-data-import.ipynb) | |
| Modeling for analytics: star schemas, views and metric views | [analytics-modeling](databricks/analytics-modeling.ipynb) | |
| AI/BI dashboards, sharing and alerts | [aibi-dashboards](databricks/aibi-dashboards.ipynb) | |
| Genie: One, Agents, Ontology and Code | [genie](databricks/genie.ipynb) | |

Independent study resource. Not affiliated with or endorsed by Databricks.
