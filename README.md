# Intellihack_MinionZ_03

## Overview
Welcome to the **Intellihack_MinionZ_03** project! This repository contains the necessary setup and dependencies to run the application efficiently.

## How to Run inference.ipynb

This guide provides detailed instructions on how to set up and run `inference.ipynb` both locally and on Google Colab.

---

## Running Locally

### 1. Clone the Repository
Open a terminal and run:
```sh
git clone <repo-link>
cd <repo-folder>
```

### 2. Create a Virtual Environment
It's recommended to use a virtual environment to manage dependencies. Run the following commands:

For Windows:
```sh
python -m venv venv
venv\Scripts\activate
```

For macOS/Linux:
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
Run the following commands to install the necessary dependencies:
```sh
pip install python-dotenv
pip install langchain-community
pip install -U duckduckgo-search
pip install langchain-google-genai
pip install chromadb
pip install PyMuPDF
pip install llama-cpp-python
```

### 4. Run the Notebook
- Open `inference.ipynb` in Jupyter Notebook or VS Code.
- Run the **Background Setup** cell to complete the necessary setup.
- Once the setup is complete, you can run the **Inference** cells to interact with the model.

---

## Running on Google Colab

### 1. Open the Notebook in Colab
- Upload the repository to your Google Drive or open `inference.ipynb` directly in Google Colab.
- Ensure all required files and folders (`chroma_db`, `dataset`, `static`, and `qwenfinal.gguf`) are uploaded to the Colab session storage.

### 2. Install Dependencies
Create a new code cell at the top of the notebook and run the following command:
```sh
!pip install python-dotenv langchain-community duckduckgo-search langchain-google-genai chromadb PyMuPDF llama-cpp-python
```

### 3. Run the Notebook
- Execute the **Background Setup** cell to set up the environment.
- Once the setup is complete, run the **Inference** cells to interact with the model.

---

By following these steps, you will successfully set up and run the inference notebook either locally or on Colab.



