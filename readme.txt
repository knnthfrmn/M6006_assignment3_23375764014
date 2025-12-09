We began the data cleaning process by uploading and scoping the data. 
Beginning with the happiness dataset, we added a column to each year's independent datasets to show which year they correspond to before merging them together to create a dataframe. 
We also renamed columns for consistency, and dropped any columns that didn't appear in the datasets for all years.
This allowed us to concatenate each happiness dataframe into one big dataframe
Then, we looked at which countries didn't exist in all dataframes, and resolved those which could be resolved
