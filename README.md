# Search-Transaction-by-Arguments-Big-Data-Hadoop-Project-
Search the Particular transcation records as per the condition passed as an argument.

To Run:
#Step 1:Make jar file of the project 
#Step 2: Copy this jar file into Hadoop
#Step3:Copy the input file into HDFS:
Command:
hadoop fs -copyFromLocal  /Local_address_path /HDFS_address
#Step4:To Run it on the Apache Hadoop Framework:
Command:
hadoop jar /jar_file_address /Uid_to_be_Searched /input_file_address /output_file_name

To view the Output:
hadoop fs -cat /output_file_part_name

