# Plant Disease Recognition System

This project is a web-based application for detecting plant diseases using a trained TensorFlow model. The system allows users to upload an image of a plant, analyze it, and identify potential diseases. It is built using Streamlit for the front-end interface and TensorFlow for the machine learning model.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Requirements

Ensure you have the following installed:

- Python 3.7+
- TensorFlow
- Streamlit
- Numpy
- Pandas

You can install the required dependencies using `pip`:

```bash
pip install streamlit tensorflow pandas numpy
```

### Clone the Repository

```bash
git clone https://github.com/offline-keshav/Plant_Disease_Prediction_ML_Model
cd Plant_Disease_Prediction_ML_Model
```

### Model File

The trained model should be placed in the root directory of the project. Ensure the file is named `trained_model.keras`. 

## Usage

To run the Plant Disease Recognition System, use the following command:

```bash
streamlit run main.py
```

After launching, the application will be accessible in your web browser.

### Sidebar Options

- **Home:** Displays a brief overview of the project, along with a description of how to use the system.
- **About:** Contains information about the dataset used to train the model.
- **Disease Recognition:** This is where you can upload an image of a plant leaf for disease detection.

### Disease Recognition

1. Navigate to the **Disease Recognition** page.
2. Upload an image of the plant’s leaf.
3. Click the "Show Image" button to display the uploaded image.
4. Click the "Predict" button to let the model analyze the image and display the predicted disease.

## Dataset

The dataset used for training the model consists of 87,000+ RGB images of plant leaves categorized into 38 different classes, representing both healthy and diseased plants. It is split into training (80%) and validation (20%) sets. A small test dataset (33 images) is also used for predictions.

### Dataset Structure:

- **Train:** 70,295 images
- **Test:** 33 images
- **Validation:** 17,572 images

## How It Works

The application takes an image input, processes it using the pre-trained TensorFlow model, and predicts the class of the plant disease. The predictions are based on a classification of 38 different diseases.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

---

