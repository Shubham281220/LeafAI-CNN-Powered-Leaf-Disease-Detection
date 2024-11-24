# Grape Leaf Disease Detection Using Deep Learning

This project is a deep learning-based approach to detecting and classifying grape leaf diseases. It employs a custom Convolutional Neural Network (CNN) to identify diseases like Black Rot, Esca, Phylloxera, and others, helping farmers automate the early detection of grapevine diseases for better yield and quality.

---

## About the Project

Grape leaf diseases cause significant damage and economic losses in agriculture. This project addresses the problem by building an automated system for disease detection. The system:
- Uses a custom CNN for image processing and classification.
- Achieves high accuracy by leveraging a dataset of 6 types of grape leaf conditions: Healthy, Black Rot, Esca, Leaf Blight, Powdery Mildew, and Phylloxera.
- Offers an early disease detection mechanism to aid farmers in managing their crops effectively.

---

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Grape-Leaf-Disease-Detection.git
   cd Grape-Leaf-Disease-Detection
Install Dependencies: Create a Python virtual environment and install the required libraries:

bash
Copy code
python -m venv env
source env/bin/activate  # On Windows: .\env\Scripts\activate
pip install -r requirements.txt

Prepare the Dataset:
Download the dataset from here.
Extract the dataset into the project directory.

Run the Notebook: Open CNN_leaf_disease_detection_coloured.ipynb in Jupyter Notebook or any IDE that supports notebooks, and execute the cells to:
Train the CNN model.
Evaluate the model.
Predict leaf disease on a test image.

Use Case
This project has applications at various scales:
Small Scale: Automates routine detection tasks for farmers, reducing dependency on manual inspection.
Industry Level: Enhances automation in agriculture by integrating disease detection with precision farming. This can help agribusinesses improve productivity and profitability.
Research and Development: Provides a foundation for developing more advanced models to tackle plant diseases across different crops.

Dataset
The dataset consists of:
950+ training images and 200+ testing images for each of the 6 categories.
Images resized to 256x256 pixels for processing.

Conclusion
The proposed system achieves 96.25% accuracy using a custom CNN model. It provides a reliable and efficient solution for grapevine disease detection, with potential for further improvement using real-world datasets and refined CNN architectures.