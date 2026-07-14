# AWS Glue
AWS Glue is a fully managed, serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development. It automates the ETL (Extract, Transform, Load) pipeline process, allowing users to focus on building workflows rather than managing infrastructure.

- https://aws.amazon.com/glue/
- https://docs.aws.amazon.com/glue/latest/dg/what-is-glue.html
- https://docs.aws.amazon.com/glue/
- https://docs.aws.amazon.com/prescriptive-guidance/latest/serverless-etl-aws-glue/aws-glue-etl.html
- https://docs.aws.amazon.com/glue/latest/dg/how-it-works.html
- https://aws.amazon.com/video/watch/b17f39da7a6/
- https://docs.aws.amazon.com/databrew/latest/dg/what-is.html

- https://github.com/aws-samples/aws-glue-samples
- https://github.com/awslabs/aws-glue-libs
- https://github.com/awslabs/aws-glue-data-catalog-client-for-apache-hive-metastore
- https://github.com/aws-samples/aws-glue-test-data-generator
- https://github.com/aws-samples/aws-glue-local-development
- https://github.com/awslabs/aws-glue-schema-registry
- https://github.com/aws-samples/aws-glue-jobs-unit-testing
- https://github.com/aws-samples/aws-glue-cdk-baseline
- https://github.com/aws-samples/aws-glue-samples
  

---

## Core ComponentsData Catalog: 

- A centralized metadata repository that stores schemas, table definitions, and connection details, making data easily searchable across AWS without physically moving it.
- Crawlers: Automated programs that scan data sources, infer schemas (e.g., CSV, JSON, Parquet), and automatically populate or update the Glue Data Catalog.
- ETL Jobs: Serverless Apache Spark or Python environments that run transformations. Jobs can be triggered by time-based schedules or specific data events.
- Data Quality: Built-in tools to automatically monitor and enforce data quality rules across your pipelines.


---

## Development Options

### AWS Glue accommodates different skill levels through its suite of specialized tools:

- Glue Studio: Provides a visual, drag-and-drop interface for building complex ETL pipelines without writing code.
- Glue DataBrew: A visual data preparation tool featuring a spreadsheet-like interface with over 250 built-in transformations for cleaning and normalizing data.
- Notebooks & Interactive Sessions: Allows data engineers and data scientists to interactively develop, explore, and test Spark code in IDEs or Jupyter-style notebook.

---

## Use CasesData Lakes & Warehouses: 
- Seamlessly pull raw data from over 100 native sources (like Amazon S3, RDS, and Redshift) and load it into analytics platforms.
- Zero-ETL: Connect directly to sources to process and modernize Apache Spark jobs instantly using built-in generative AI capabilities.
- Machine Learning Prep: Automate feature engineering and streamline raw data transformation to feed downstream ML models on platforms like Amazon SageMaker.

---

