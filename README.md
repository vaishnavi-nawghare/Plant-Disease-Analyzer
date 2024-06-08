# Plant-Disease-Analyzer


This repository contains the source code for the Plant Disease Analyzer application, a tool designed to help identify and analyze plant diseases using machine learning models.

## Installation and Setup

Follow the steps below to clone the repository, set up the virtual environment, install required libraries, and run the application.

### 1. Clone the Repository

```bash
git clone https://github.com/rudrakshkarpe/Plant-Disease-Analyzer.git
cd Plant-Disease-Analyzer
```

### 2. Create a Virtual Environment and Install Required Libraries

```bash
python -m venv env
source env/Scripts/activate
pip install -r requirements.txt
```

### 3. Create the Models Directory

```bash
mkdir models
```

Download the necessary models and place them in the `models` directory. You can find the models [here](source_link).

### 4. Run the Application

```bash
python app.py
```

### 5. Open the Application in the Browser

Navigate to the following URL in your web browser:

```
http://127.0.0.1:5000
```

## Usage

1. Open the application in your browser.
2. Upload an image of a plant leaf.
3. The application will analyze the image and provide information about the potential disease affecting the plant.


---

Thank you for using Plant Disease Analyzer! We hope this tool helps you in identifying and managing plant diseases effectively.
