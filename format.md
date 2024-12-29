# delta format

[Saving data in delta format](https://learn.microsoft.com/en-us/training/modules/work-delta-lake-tables-fabric/3-create-delta-tables#saving-data-in-delta-format)
- headless: no table definition in the metastore will be created. It output files only
  - The 3rd way, compared to save dataframe as delta table (headful) or create the table definition (only head)
- targeting a path, it will generates Parquet files + **_delta_log** folder.
