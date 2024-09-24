
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
1-Data Loading.
2-Baseline Model Building
3-Training the Model and testing the model
4-Building an augmented model
5-Training the augmented model and testing the model
6-Countering Class Imbalance with augmentor
7-Building the final model
8-Training the final model and testing the model
9-Verifying the model


Conclusion:
The training accuracy and validation accuracy are nearly identical, indicating a good fit for the model. Additionally, the training loss and validation loss are also close to each other, further confirming the model's good fit. With a validation accuracy of 0.83, the model successfully classifies images with 83% accuracy, which is a strong performance.
However more epochs will surely increase accuracy more for above 90%

Technologies Used:
Python,
Tensorflow,
Keras,
Augmentor,
Matplotlib,
NumPy

Contact
Created by [@MaimanaKowtly] - feel free to contact me!

License
This project is open source and available under the MIT License.
