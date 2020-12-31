Question 1 - How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
Answer - Two config parameters that seem to influence were processedRowsPerSecond and inputRowsPerSecond. 

Question 2 - What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?
Answer - The throughput seemed to get better by altering the two parameters maxOffsetsPerTrigger and maxRatePerPartition 
