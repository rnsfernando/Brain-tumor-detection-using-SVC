# Brain Tumor Detection using SVC

This project focuses on the detection of brain tumors using a Support Vector Classifier (SVC) model. It leverages machine learning techniques to classify brain MRI images as either having a tumor or not.

## Project Overview

Brain tumor detection is a critical task in medical image analysis. Early and accurate detection can significantly improve treatment outcomes and patient survival rates. This project utilizes an SVC model, a powerful supervised learning algorithm, to distinguish between healthy brains and those with tumors.

## Dataset

The dataset consists of brain MRI images, categorized into two classes:

* **no_tumor:** Images of brains without tumors.
* **pituitary_tumor:** Images of brains with pituitary tumors.

The dataset is split into training and testing sets to train and evaluate the model.

## Methodology

1. **Data Preprocessing:**
   - Images are loaded and converted to grayscale.
   - Images are resized to a uniform size (200x200 pixels).
   - Pixel values are normalized to a range of 0 to 1.
2. **Feature Extraction:**
   - Images are flattened into a 1D array of pixel values.
3. **Model Training:**
   - An SVC model is trained using the training data.
   - The model learns to differentiate between the two classes based on the extracted features.
4. **Model Evaluation:**
   - The trained model is evaluated on the testing data using accuracy as the metric.
5. **Prediction:**
   - The model is used to predict the presence or absence of a tumor in new MRI images.

## Results

The SVC model achieved high accuracy on both the training and testing sets, indicating its effectiveness in classifying brain tumors.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

## Usage

1. Clone the repository: `git clone <repository_url>`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook brain_tumor_detection.ipynb`

## Contributing

Contributions to this project are welcome. If you find any bugs or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Disclaimer

This project is intended for educational and research purposes only. It should not be used for actual medical diagnosis. Always consult with a qualified healthcare professional for any health concerns.
