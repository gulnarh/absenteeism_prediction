
# Absenteeism prediction

This is a data analyzing project that mainly focuses on cleaning and manipulating data to prepare it for the further step where logistic regression has been applied as machine learning techniques. Using this model we can have absenteeism probability and prediction. In the end, the model has been aplied to the new data set and the the result has been visualized by Tableau.



## Project Structure

There are 2 Jupiter Notebook files are for cleaning and training/testing the dataset.

Moreover, a dataset is to be familiar of the structure of it and to use the model for similar dataset.

And finally, there are  3 files that are ready to apply to new data set to predict absenteeism: 
    
    1. Absenteeism_module which developed according to 2 above-mentioned .ipynb files,
    2. model, 
    3. scaler.

## Usage
In order to use these 3 files firstly absenteeism_module should be import:

    from absenteeism_module import *

Then after unpickling the model and scaler the methods that are in the module are ready to use:
    
    model = absenteeism_model('model', 'scaler')
    model.load_and_clean_data('file_name.csv')
    model.predicted_outputs()
  
