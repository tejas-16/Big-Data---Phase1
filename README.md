# Big-Data---Phase1
Project on Sqoop and Hive -
Created database on rdbms table and created table, loads the data into the created table and imported the data into hadoop using sqoop import as avro on staging location.
After  importing -----
Created a Hive database and created a managed table using the avsc on the staging location also Created external table using AVRO with partitions year month and day after that Inserted into external table  with Partition date column source date_time ---- with filter web_info='JAKARTA' ----IN HIVE
