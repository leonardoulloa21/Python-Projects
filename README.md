# Python-Projects
Projects releated to Data Engineering and Analytics.
1. Python - Azure ComosDB To Teradata:
   Extract data from a Azure Cosmos DB container, decryping columns, transforming datatime columns, reindexing columns to match the load table schema in Teradata. I used two Teradata tables for this, intermediate and final. This script was made to handle 20k-30k records. If runtime becomes a problem for larger datasets, try parameterizing by dates.
