# LeafAI: CNN Powered Leaf Disease Detection

This project implements a deep learning-based approach to detect and classify grape leaf diseases. By employing a custom Convolutional Neural Network (CNN), it identifies diseases such as Black Rot, Esca, Phylloxera, and others, helping farmers automate early detection for improved yield and quality.

---

## About the Project
Grape leaf diseases cause significant damage and economic losses in agriculture. This project addresses the issue by developing an automated disease detection system. The key features include:

- **Custom CNN Model:** Designed for image processing and classification.
- **High Accuracy:** Achieves 96.25% accuracy on a dataset containing 6 grape leaf conditions:
  - Healthy
  - Black Rot
  - Esca
  - Leaf Blight
  - Powdery Mildew
  - Phylloxera
- **Early Detection Mechanism:** Assists farmers in managing crops effectively, reducing losses.

---

## How to Run

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/Grape-Leaf-Disease-Detection.git
cd Grape-Leaf-Disease-Detection
```

### Step 2: Install Dependencies
1. Create a Python virtual environment and activate it:
   - **For macOS/Linux:**
     ```bash
     python3 -m venv env
     source env/bin/activate
     ```
   - **For Windows:**
     ```bash
     python -m venv env
     .\env\Scripts\activate
     ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Step 3: Run the Notebook
- Open the `CNN_leaf_disease_detection_coloured.ipynb` notebook in Jupyter Notebook or any IDE supporting notebooks.
- Execute the cells to:
  1. Train the CNN model.
  2. Evaluate the model.
  3. Predict leaf disease on a test image.

---

## Use Case
This project offers diverse applications across different scales:

### Small Scale:
- Automates routine disease detection tasks for farmers, minimizing the need for manual inspection.

### Industry Level:
- Enhances automation in agriculture through integration with precision farming, improving productivity and profitability for agribusinesses.

### Research and Development:
- Provides a foundation for developing more advanced models targeting plant diseases in various crops.

---

## Dataset
The dataset used in this project consists of:
- Over **950 training images** and **200 testing images** for each category.
- Images resized to **256x256 pixels** for efficient processing.

---

## Conclusion
The system achieves an impressive **96.25% accuracy** using a custom CNN model. It offers a reliable and efficient solution for detecting grapevine diseases, with potential for further improvement using real-world datasets and refined CNN architectures.

---

## Project Highlights
- **Machine Learning Framework:** TensorFlow and Keras
- **Languages:** Python
- **Image Processing Tools:** OpenCV, PIL
- **Environment:** Jupyter Notebook

This project demonstrates how deep learning can revolutionize agricultural practices by enabling accurate and automated detection of plant diseases.
