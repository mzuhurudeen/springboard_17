**Springboard Data Science Career Track**
Muneer Zuhurudeen
Project: Parsing JSON dataset in order to analyze with newly acquired Pandas skills. 
Key concepts: Reading in a json file, nested key value pairs, flattening nested elements into a table, merging data sets. 

The data used can be found in the "data" folder in this repository. 

Assignment:

Using data in file 'data/world_bank_projects.json',

1. Find the 10 countries with most projects
1. Find the top 10 major project themes (using column 'mjtheme_namecode')
1. In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in.
	
Method (for more information, see comments in code)
1. Read in necessary libraries and data
1. Get a sense of what the dataset looks like
1. Rank top 10 countries with the most projects (pandas knowledge and sytax used)
1. Load in json file and flatten based on id (unique element)
1. Sort top 10 themes present 
1. Because some rows in the dataframe don't have a name, create a lookup table of id by name
1. Merge the lookup onto the original dataframe to fill in the blanks
