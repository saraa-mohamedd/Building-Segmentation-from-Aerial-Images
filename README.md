# Building Segmentation from Aerial Images Using U-Net With Attention

Welcome to our Building Segmentation using Aerial Images Deep Learning Project! Below are steps to get the model up and running as you'd
 like it to.



## Data

The (SpaceNet) dataset used in this project is available for download only through AWS CLI. To avoid any cumbersomeness, provided is the [link](https://drive.google.com/file/d/1spEIP-Fju2UMxzTP0JsmZOzEZfETYAoR/view?usp=sharing) to download a zipped folder containing all required data dependencies for this project. Upon unzipping the `data` folder, place it in the directory of the project. 

> Note: the `data_preprocessing.ipynb` notebook was used to generate the ground truth images in the data.zip folder, as SpaceNet offers ground truth labels in the form of GeoJSON files and not images. If you'd like to see `data_preprocessing.ipynb` in action, feel free to delete the "buildingMaskLabels" folder in the unzipped data directory, and run the notebook before moving onto the main `network.ipynb` notebook.

 

## Training the Model

Training our model is very simple. All you need to do is make sure the paths are properly defined in the code cells of the `network.ipynb` notebook, and run the entire notebook as required. 

To load the pre-trained weights provided, simply uncomment the last two lines in the code cell right before training. 


## Testing the Model

To test the model on the test dataset, simply load the desired model weights by altering the path name to the name of your saved model, and run the rest of the notebook.

If you'd like to test the model without going through training, simply do as above, but without running the training cell.

## Project Information & Visuals

For more information about the project, click [here]{} to view a visual of the project, its structure, and our results. Click [here][] for a website description of the project.
