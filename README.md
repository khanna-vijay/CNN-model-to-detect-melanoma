# Melanoma Detection using Convolutional Neural Networks

> This project develops a custom convolutional neural network (CNN) model to classify skin lesions as melanoma or other types of skin conditions based on image data. Melanoma is a severe form of skin cancer that can be fatal if not diagnosed early. Our model aims to assist dermatologists by automating the initial screening process, potentially saving lives through earlier detection.

## Table of Contents
- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## General Information
- **Background**: Melanoma accounts for 75% of skin cancer deaths. Early detection is crucial to improving survival rates. Automating the detection process using machine learning can significantly assist dermatologists.
- **Business Problem**: The project addresses the need for efficient, accurate melanoma detection to reduce the manual effort and potential human error in diagnosing skin cancer.
- **Dataset**: The dataset used in this project comprises 2357 images sourced from the International Skin Imaging Collaboration (ISIC). These images include various skin conditions, but focus primarily on melanoma and moles.

## Conclusions
- Our initial model training indicated potential overfitting, addressed through data augmentation techniques.
- After augmentation, the model showed improved generalization on validation data.
- Handling class imbalances further stabilized the training process, reducing bias towards more frequent classes.
- The final model, trained with balanced data and additional epochs, achieved satisfactory accuracy and might be ready for a pre-clinical evaluation phase.

## Technologies Used
- TensorFlow - 2.4
- Keras - 2.4.3
- NumPy - 1.19.5
- Augmentor - 0.2.8

## Acknowledgements
- This project was inspired by the need for advancements in medical imaging and automated disease detection technologies.
- Dataset provided by the International Skin Imaging Collaboration (ISIC).
- Special thanks to [TensorFlow tutorials](https://www.tensorflow.org/tutorials) for guidance on CNN architectures.

## Contact
Created by [@khanna-vijay] - feel free to contact me!
