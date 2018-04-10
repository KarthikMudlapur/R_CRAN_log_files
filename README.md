# R_CRAN_log_files

Analysis of R CRAN log files for the month of October 2017 in Hadoop environment using Apache Pig and Sqoop .

1. Create a for loop in R studio and download all the log files of all the days for the entire month of October 2017. (approx 7.5 GB of data)

2. Upload the downloaded files into the hadoop environment(hdfs).

3. Use Apache Pig (Pig latin) to query the answers to the questions. Store the results outside the Pig environment.

4. Export the results into MySQL database using Apache Sqoop. Query and check if the tables are present.

5. Connect MySQL database to the R environment to analyse further.

6. Analyze the log files further in R and create visualizations.
