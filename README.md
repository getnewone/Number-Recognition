# Digit Recognition

This project demonstrates handwritten digit recognition using a Logistic Regression model on the MNIST dataset. The Jupyter Notebook (digi_recognization.ipynb) fetches the dataset, preprocesses data, trains the model, evaluates its performance, and provides a visual prediction function.

## Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- pip (package installer)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd "Digit Recognition"
   ```
2. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   # Windows:
   .\venv\Scripts\activate
   # Linux/Mac:
   source venv/bin/activate
   ```
3. Install the required packages:
   ```bash
   pip install numpy scikit-learn matplotlib
   ```

## Running the Notebook
1. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```
2. Open the file `digi_recognization.ipynb`.
3. Run the cells in order to:
   - Load and preprocess the MNIST dataset.
   - Train the Logistic Regression model.
   - Evaluate the model’s performance.
   - Use the `predict_and_display` function to showcase predictions.

## Troubleshooting
- Ensure you have an active internet connection when fetching the MNIST dataset.
- Confirm that all dependencies are installed correctly.

Enjoy testing the digit recognition model!
