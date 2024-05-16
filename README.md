# This Repo

This repo contains learning materials for the Data Engineer Associate certification from Databricks

# Intro

Databricks is a data and AI company. Databricks is a Spark based modern analytics platform.  Databricks takes benefits of both data lake and data warehouse and combines them into lakehouse platform. 

# Overview

Below figure is an overview of the Databricks platform. 
![overrview](overview.png)

# Architecture
![architecture](archi.png)

# Clusters
![cluster](clusters.png)

Comparing the 2 different cluster types
![cluster_types](cluster_types.png)

# Magic commands

Magic commands are special type of commands in Databricks which is mainly used to override default languages, run utilities/auxillary commands etc.
Few magic commands are:
![magic_commands](magic_commands.png)

**DBUTILS** - library of utility functions
![dbutils](dbutils.png)

# DB Repos
Repos let you use Git functionality such as cloning a remote repo, managing branches, pushing and pulling changes and visually comparing differences upon commit. We can connect Git Repo to DB repo.


# DB Notebooks
Learn more about Databricks Notebook in [Notebooks_basics.ipynb](Notebooks_basics.ipynb)

# Data Objects
Different data objects in databricks are:
![data-objects](data_objects.png)

2 types of tables in Databricks:
![table_types](type_of-tables.png)

# Reading files
The [DE 2.1 - Querying Files Directly.sql](DE%202.1%20-%20Querying%20Files%20Directly.sql) file is a notebook which explains how to query files directly.

The [DE 2.2 - Providing Options for External Sources.sql](DE%202.2%20-%20Providing%20Options%20for%20External%20Sources.sql)shows how to create tables using external data sources

# Cleaning Data and Transformations
The [DE 2.4 - Cleaning Data.sql](DE%202.4%20-%20Cleaning%20Data.sql) has cleaning logic. It inspects missing data, deduplicate rows, deduplicate rows based on specific columns, validations, playing around date formats and regex.

The [DE 2.5 - Complex Transformations.sql](DE%202.5%20-%20Complex%20Transformations.sql) file contains complex transformations like working with nested data, schema_of_json(), from_json(), explode(), size(), collect_set(), flatten(), array_distinct(), joins and pivot table

The DE 3.1 descibes more of schemas and tables icnluding, managed and external tables: very important

The DE 3.2 explains delta tables: CTAS stmts, Filtering and Renaming Columns from Existing Tables, **Generated Columns**, table constraints , Additional Options and Metadata, and cloning tables.




