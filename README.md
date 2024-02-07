# Traffic Sign Classifier

Traffic Sign Classifier classifies images of road traffic signs using the Convolutional Neural Network models: VGG-16 and LeNet

## Instructions to run the files:

It is advised to move the trafficsigns_dataset.zip outside the project folder, to avoid changing path in the code.

Run the ipynb files in the following order:

1. TrafficSignClassifier.ipynb: creates all models, saves them and evaluates them. Creates a csv file called 'trafficsigns_dataset.csv' inside the trafficsigns_dataset folder.

2. create_csv.ipynb: unzips the folder 'ASSORTED_ML.zip' and creates a csv file 'external_images_actual.csv' inside the project folder. This contains all the actual sign shapes and types of the external images.

3. external_image_testing.ipynb: testing on external images is done in this file. It unzips the file 'ML_TESTING.zip' and after formatting images, adds them to the empty folder 'external_images'. Creates a csv called 'external_data.csv' inside the project folder.

## Additional information:

'external_images' folder: contains the formatted images to be used for testing of external images (populated after running external_image_testing.ipynb)

'ASSORTED_ML.zip': contains same structure as dataset, and contains all external images sorted according to sign-shape and sign-type

'ML_TESTING.zip': contains all the raw images collected individually for testing 
