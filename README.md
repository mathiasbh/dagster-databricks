# dagster-databricks
Dagster coupled to databricks (freebricks)


## Goals

* Continue on dagster-offline
* Connect to Freebricks (databricks)
  * use REST API calls (databricks)
  * use dagster-databricks
* Write data to tables
* Connect freebricks to some secondary git or use folder structure in this github project to separate logic
* Create job that runs on databricks
  * Something very simple
  * Run notebook
    * run from path from string
    * add some abstraction to find notebook path (fetch_from_workspace?)
    * abstraction from file location of notebook
  * Unity Catalog job (governance)
    - schema creation
    - permission

## Later goals
* Machine learning
  * Couple dagster and Databricks jobs
  * Save machine leraning models to Databricks Models 
  * Serving