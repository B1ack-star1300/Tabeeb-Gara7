# Tabeeb-Gara7
=================
Briefly describe what your application does here (e.g., "A desktop application that uses machine learning to analyze text and provide embeddings/classifications"). 

## 📁 Project Structure and Files

*   **`Wag3-Elqalb.ipynb`** (or your specific `.ipynb` name): The core Jupyter Notebook used for interactive development, prototyping the neural network, and debugging the application logic before exporting to a standalone script.
*   **`gui.py` / `app.py`**: The main Python script containing the Tkinter graphical user interface. This file binds the user input from the desktop window to the backend machine learning models.
*   **`requirements.txt`**: A list of all Python dependencies required to run the project.

*(Note: Add any other files here, such as dataset CSVs or saved model `.h5` files, and briefly state what they contain.)*

## 🛠️ Tools and Technologies Used

This project relies on several specific libraries. Here is why each was chosen:

*   **Python 3.x**: The core programming language, chosen for its extensive ecosystem of machine learning and data science libraries.
*   **Tkinter**: The standard GUI toolkit for Python. 
    *   *Why we use it:* It comes built-in with Python, meaning it requires no extra heavy installations. It is perfectly suited for building lightweight, functional desktop interfaces for data tools.
*   **TensorFlow / Keras**: The primary deep learning framework.
    *   *Why we use it:* Keras (running on top of TensorFlow) provides an intuitive API for building, training, and running neural networks. *(Note: This project relies on CPU inference for Windows environments since native TF 2.11+ GPU support is Linux/WSL2 exclusive).*
*   **Sentence-Transformers (`all-MiniLM-L6-v2`)**: A Python framework for state-of-the-art text and image embeddings.
    *   *Why we use it:* The `all-MiniLM-L6-v2` model is incredibly fast and lightweight while still providing high-quality semantic text embeddings. It is ideal for running locally on a desktop without requiring a massive GPU.
*   **NumPy**: The fundamental package for scientific computing in Python.
    *   *Why we use it:* Used under the hood by TensorFlow and Sentence-Transformers to handle multi-dimensional arrays and matrix operations efficiently.

## 🚀 Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone [your-repository-url]
   cd [your-repository-folder]
