In this data file, each row corresponds to a Web table. There are three columns for each row, separated by tabs. 

The first column has table ids. 
The second column has all rows from the same table, concatenated together and separated by underscores. Cell delimiters are removed, and this is the testing data used by our parsing algorithms. 
The third column has the ground truth tables, where true cells boundaries (as they were extracted from Web pages) are denoted by vertical bars.