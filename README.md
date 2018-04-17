# TEGRA-Table-Segmentation
TEGRA: Table Extraction by Global Record Alignment

### Overview
This is the benchmark data set used in our experiments described [here](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Main.pdf). 

The data set has 10K randomly sampled Web tables. To automatically test table segmentation, for each table, we take out column seperators and concatenate all cells in the same row together. This results in 10K test where the ground truth are original tables.

### Data set description
Each row in the file corresponds to a Web table. There are three columns for each row, separated by tabs. 

* The first column has table ids. 

* The second column has all rows from the same table, concatenated together and separated by underscores. Cell delimiters are removed, and this is the testing data used by our parsing algorithms. 

* The third column has the ground truth tables, where true cells boundaries (as they were extracted from Web pages) are denoted by vertical bars.
 
