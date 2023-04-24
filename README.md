# Diabetes Prediction using SVM

This project aims to predict the onset of diabetes in patients using SVM (Support Vector Machine) algorithm. The dataset used for training and testing is the Pima Indians Diabetes Database available on Kaggle.

## Requirements
The following libraries are required to run the project:

* scikit-learn
* numpy
* pandas

To use the UI, you also need the following:

* gradio

## Usage

1. Clone the repository
```
git clone https://github.com/<username>/<repository-name>.git

```

2. Install the required libraries.
3. Run the model.py file to train the model and save it.
4. Open the URL displayed in the console in a browser to access the UI.

## How to Use the UI

1. Enter the values for the features in the form provided.
2. Click on the "Predict" button to get the prediction.

## Standardization
The data is standardized using the StandardScaler class from scikit-learn. Standardization is performed to ensure that each feature is on the same scale and has a mean of 0 and a standard deviation of 1. This helps the SVM algorithm to converge faster and produce better results.

## Note

The dataset used in this project is not a substitute for a medical diagnosis. The purpose of this project is purely educational, and the predictions made by the model should not be used for medical purposes.

## Credits
This project was created by Abhishek Tyagi. The dataset used in this project was obtained from Kaggle, and the UI was built using Gradio.

## License
This project is licensed under the [Apache-2.0](https://github.com/abhishektyagi2912/Diabetes_machine_learning/blob/master/LICense).







