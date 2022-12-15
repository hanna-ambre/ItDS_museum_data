# ItDS_museum_data code - How to run it

The project code is in the file "project_code.ipynb". It is a Jupyter notebook file. The first cell is to use Google colab. If you run the project in your local computer, you don't need to run this block. To run the code, you need to download the files from the Kaggle competition and put them in the same folder as the project code. The files you need to download are: unique_types.csv, train.csv and test.csv. The competition can be found here: https://www.kaggle.com/competitions/caps-in-museums-data-part-2/data.

Firstly, run the imports cell and the cells in the 'Read data from files and preprocess the data' part. This will read in the data and add columns for frequently appearing words and column values, which will be important later. You can use the code in part 'Save preprocessed data to file or read it from file' to save the preprocessed data so that the next time you want to use it, you wouldn't have to preprocess it again.

Then run the 'Separating original trainset and testset' section to separate the traintest dataset into the train and test datasets and to get a list of all of the columns, excluding 'type'.

To test different models with validation data and create the variable for the model, run the next part titled 'Creating validation set and using it to find the best model'.

Finally, to test the model on the test dataset and create the prediction csv-file, run the 'Training on the whole trainset' section.

The last part of the code (in the 'code to tune the hyperparameters for decision tree and random forest' section) shows what we did to tune the hyperparameters.
