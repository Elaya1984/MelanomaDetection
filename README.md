# Melanoma-Detection

## Table of Contents

- [Melanoma-Detection-using-using-custom-cnn](#melanoma-detection-assignment-using-custom-cnn)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Algorithms Used](#algorithms-used)
    - [Dataset Information](#dataset-information)
  - [Steps Involved](#steps-involved)
  - [Results](#results)
    - [Baseline Model](#baseline-model)
    - [Augmented Model](#augmented-model)
    - [Final Model](#final-model)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Contact](#contact)


<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Algorithms Used

Convolutional Neural Network

### Dataset Information

This assignment uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Steps Involved

- Data setup
- Initial Model 
- Train Initial Model and test
- Building an model with dropout layers
- Train model with dropout layers and test
- Class Imbalance with augmentor
- Building the model with augmentation
- Training the final model with augmentation and testing the model
- Final Result

## Results

### Initial Model Result

Initial Model Accuracy and Loss 
![Alt text](InitialModelResult.png)

### model with dropout layers result

Model with dropout layers Accuracy and Loss
![Alt text](DropoutLayersModelResult.png)

### Final Model

Augmented Model Accuracy and Loss
![Alt text](AugmentedModelResult.png)

# Conclusion

The model created with augmenter has an accuracy of 0.9640 at 30 epochs and a loss of 0.8. The model with augmented the data and countering class imbalance  predict the class of the lesion with a high accuracy.The data augmentation and countering class imbalance improved the accuracy of the model.

# Technologies Used

- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy

# Contact

Created by [@Elaya1984] - feel free to contact me!

