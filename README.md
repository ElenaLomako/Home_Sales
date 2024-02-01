# Home_Sales

All code is completed. 
Please nore that it wasn't clear if the following query "query that filters out the view ratings for each year with average price of greater than or eqaul to $350,000" requires the view rating to be for each year. So I made two versions of it and ran runtime for each versions and compared it. 

TMy results are as follows: runtime is smalled for cached versions vs uncached, whereas runtime with parquet dataframe was longer than both: cached and uncached versions.