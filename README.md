# ItDS_museum_data code - How to run it

Firstly, run the imports cell and the cells in the 'Read data from files and preprocess the data' part. This will read in the data and add columns for frequently appearing words and column values, which will be important later. You can use the code in part 'Save preprocessed data to file or read it from file' to save the preprocessed data so that the next time you want to use it, you wouldn't have to preprocess it again.

Then run the 'Separating original trainset and testset' section to separate the traintest dataset into the train and test datasets and to get a list of all of the columns, excluding 'type'.

To test different models with validation data, run the next part titled 'Creating validation set and using it to find the best model and create the variable for the model.

Finally, to create the model and prediction csv-file, run the 'Training on the whole trainset' section.
