# Sales-SQL-Data-Warehouse-Project
SQL Data Warehouse Project Description This project focuses on designing and implementing a SQL‑based Data Warehouse that supports strategic and operational decision‑making. The warehouse is built as a subject‑oriented, integrated, time‑variant, and non‑volatile repository, ensuring consistent, historical, and reliable data for analytics. 
This project focuses on designing and implementing a SQL‑based Data Warehouse that supports strategic and operational decision‑making. The warehouse is built as a subject‑oriented, integrated, time‑variant, and non‑volatile repository, ensuring consistent, historical, and reliable data for analytics.

Extraction Phase
The project adopts a pull‑based extraction approach, where data is retrieved directly from source systems on demand. Among the two major extraction types—full and incremental—the project uses full extraction, ensuring complete data retrieval during each cycle. From the various extraction techniques available, the project employs File Parsing, enabling structured ingestion of data from flat files and semi‑structured sources. This method ensures flexibility and compatibility with diverse input formats.

Transformation Phase
The transformation stage applies a comprehensive set of processes to prepare data for analytical use. Core transformation activities include: 

Data Enrichment to enhance datasets with additional attributes

Data Integration to unify disparate sources

Derived Columns for computed insights

Normalization and Standardization to ensure consistency

Business Rules and Logic to align data with organizational requirements

Data Aggregations for summarization and reporting

Extensive data cleansing is also performed, covering duplicate removal, filtering, handling missing or invalid values, trimming unwanted spaces, data type casting, and outlier detection. These steps ensure high‑quality, trustworthy data.

Loading Phase
The loading component incorporates both batch and streaming processing capabilities, depending on data availability and business needs.

The project supports multiple load methods:

Full Load: truncate‑and‑insert, upsert, or drop‑create‑insert

Incremental Load: upsert, append, or merge

Slowly Changing Dimensions (SCD): including SCD 0 (no historization), SCD 1 (overwrite), and SCD 2 (historization), with extensibility for additional SCD types
