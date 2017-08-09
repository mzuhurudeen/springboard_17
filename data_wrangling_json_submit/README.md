Springboard Data Science Career Track
Muneer Zuhurudeen
Project: Parsing JSON dataset in order to analyze with newly acquired Pandas skills. 
Key concepts: Reading in a json file, nested key value pairs, flattening nested elements into a table, merging data sets. 

The data used can be found in the "data" folder in this repository. 

Assignment:

Using data in file 'data/world_bank_projects.json',

	1. Find the 10 countries with most projects
	2. Find the top 10 major project themes (using column 'mjtheme_namecode')
	3. In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names 				filled in.
	
Method (for more information, see comments in code)
	1. Read in necessary libraries and data
	2. Get a sense of what the dataset looks like
	3. Rank top 10 countries with the most projects (pandas knowledge and sytax used)
	4. Load in json file and flatten based on id (unique element)
	5. Sort top 10 themes present 
	6. Because some rows in the dataframe don't have a name, create a lookup table of id by name
	7. Merge the lookup onto the original dataframe to fill in the blanks
