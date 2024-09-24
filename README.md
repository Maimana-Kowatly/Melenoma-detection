Table of Content
Importing libraries
reading data
Defining Dataset Parameters
Data Visualising
Create Model
Compile the Model
Train the Model
Visualizing training results
    Findings
Create the model
Compile the model
Visualizing the results
    Findings
        find distribution classes in the training dataset
        find the class that has the least number of classes
        find the classes that dominate the data in terms proportionate number of samples
Rectify the class imbalance
distribution of augmented data after adding new images to the original training data.
    Train the model on the data created using Augmentor
    create training dataset
    create validation dataset
    Create your model (make sure to include normalization)
    Compile your model (Choose optimizer and loss function appropriately)
    Train your model
    Visualize the model results
Analyze your results here. Did you get rid of underfitting/overfitting? Did class rebalance help?
Test the model



_____________________

Data Summary:

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis,
Basal cell carcinoma,
Dermatofibroma,
Melanoma,
Nevus,
Pigmented benign keratosis,
Seborrheic keratosis,
Squamous cell carcinoma,
Vascular lesion.

Steps:
Data Loading
Baseline Model Building
Training the Model and testing the model
Building an augmented model
Training the augmented model and testing the model
Countering Class Imbalance with augmentor
Building the final model
Training the final model and testing the model
Verifying the model


Conclusion
The training accuracy and validation accuracy are nearly identical, indicating a good fit for the model. Additionally, the training loss and validation loss are also close to each other, further confirming the model's good fit. With a validation accuracy of 0.83, the model successfully classifies images with 83% accuracy, which is a strong performance.
However more epochs will surely increase accuracy more for above 90%

Technologies Used:
Python
Tensorflow
Keras
Augmentor
Matplotlib
NumPy

Contact
Created by [@MaimanaKowtly] - feel free to contact me!

License
This project is open source and available under the MIT License.