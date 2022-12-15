# ItDS_museum_data code - How to run it

Firstly, run the imports cell and the cells in the 'Read data from files and preprocess the data' part. This will read in the data and add columns for frequently appearing words and column values, which will be important later.

Then run the 'Separating original trainset and testset' section to separate the traintest dataset into the train and test datasets and to get a list of all of the columns, excluding 'type'.

To test with validation datasets, run the next part titled 'Creating validation set and using it to find the best model', but otherwise skip it.

Finally, to create the model and prediction csv-file, run the 'Training on the whole trainset' section.
