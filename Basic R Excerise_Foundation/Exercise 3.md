# Exercise 3

### It is very important that you know how to read text files from your computer into R.First, get your current working directory by typing getwd() and download mydataframe.txt from here and save it in your current working directory (or you can just paste in the text in a new file which you create on your computer).


1. Read the file into the object mydataframe using read.table(file = 'mydataframe.txt')

2. Inspect the dataframe by typing mydataframe. How does it look like? Can you spot what has gone wrong? (Everything has been put into a single column named V1)
3. The values are separated by a comma. Try importing with this in mind. How does it look like now? Is it still something wrong? (The numbers are separated into columns, but there are V1, V2 etc above the columns).
4. We want to have ‘treated1’, ‘treated2’ etc. as the column names. How can you fix this?
5. There is still one thing missing. How many columns are there in your dataframe? Use ncol(). We want to have 6 columns and use the ‘gene’ columns as the names of the rows. You can tell R which column to use as row names during import with with row.names = 1. Try this.


# Special exercise

### Can you save the dataframe as tab separated text file?
