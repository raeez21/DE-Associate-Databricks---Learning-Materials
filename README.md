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

The [DE 3.1 - Schemas and Tables.sql](DE%203.1%20-%20Schemas%20and%20Tables.sql) descibes more of schemas and tables icnluding, managed and external tables: very important

The [DE 3.2 - Set Up Delta Tables.sql](DE%203.2%20-%20Set%20Up%20Delta%20Tables.sql) explains delta tables: CTAS stmts, Filtering and Renaming Columns from Existing Tables, **Generated Columns**, table constraints , Additional Options and Metadata, and cloning tables.

The [DE 3.3 - Load Data into Delta Lake.sql](DE%203.3%20-%20Load%20Data%20into%20Delta%20Lake.sql) provides SQL syntax to process updates with Delta Lake like **insert overwrite, insert into, merge into and copy into**

The [DE 3.5 - Version and Optimize Delta Tables.sql](DE%203.5%20-%20Version%20and%20Optimize%20Delta%20Tables.sql)contains **versioning, optimisation, vaccuming** in delta lake




