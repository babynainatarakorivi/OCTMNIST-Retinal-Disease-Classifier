# OCTMNIST-Retinal-Disease-Classifier


**Overview of the dataset**

The OCTMNIST dataset is a collection of optical coherence tomography (OCT) images aimed at facilitating the classification of retinal diseases. It comprises a total of 109,309 grayscale images, each resized to 28x28 pixels for consistency and ease of use.

Dataset Composition:

Training Set: 97,477 images

Validation Set: 10,832 images

Test Set: 1,000 images

**Class Distribution**

The dataset is divided into four categories, each representing a specific retinal condition:

- Choroidal Neovascularization (CNV)

- Diabetic Macular Edema (DME)

- Drusen

- Normal

Each class contains a varying number of images, contributing to the multi-class classification task.

**Image Statistics**

Dimensions: 28x28 pixels

Color Channels: 1 (grayscale)

**Key Statistics**


**Number of Classes:**

The dataset consists of 4 classes representing different retinal diseases.

Image Shape:

Each image in the dataset has a shape of (1, 28, 28), indicating grayscale images of size 28×28 pixels.

**Class Distribution:**

Training Data:

- Class 3: 46,026 samples

- Class 0: 33,484 samples

- Class 1: 10,213 samples

- Class 2: 7,754 samples



Validation Data:

- Class 3: 5,114 samples

- Class 0: 3,721 samples

- Class 1: 1,135 samples

- Class 2: 862 samples



Test Data:

Each class has 250 samples, ensuring balanced evaluation.



**Pixel Intensity Statistics**

- Mean Intensity: -0.6283, indicating the dataset is normalized.

- Standard Deviation: 0.3844, suggesting moderate variation in pixel intensities.

- Min Pixel Value: -1.0 and Max Pixel Value: 1.0, confirming pixel values are scaled between -1 and 1.
