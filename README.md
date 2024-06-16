# Toxic Word Detection Project

This project is designed to detect hate speech, offensive language, and neutral tweets using a machine learning model. The model is trained using a dataset of tweets, and the prediction is done using a Decision Tree classifier.

## Google Colaboratory

You can run this project interactively in your browser via Google Colab by clicking the badge below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1s_y3WvT1HlGN_Q6cMjrXa8o-mYLda-75#scrollTo=FsE0VEvz4ln2)

## How to Access the Machine Learning Workflow

To access and examine the machine learning workflow, please click the badge below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kVZSjD_rgGr8MYbBu3jhjWfCZYSb6Sn1?usp=sharing)

## Project Overview

- **Data Cleaning:** The tweets are cleaned to remove unwanted characters, URLs, and punctuation.
- **Text Vectorization:** The cleaned text data is converted into numerical features using `CountVectorizer`.
- **Model Training:** A Decision Tree classifier is trained on the processed data.
- **User Interface:** An interactive interface is created using `ipywidgets` for users to input text and get predictions.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:
- Python 3.6 or higher
- Jupyter Notebook or Jupyter Lab
- Required Python packages (check requirements.txt)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Mrmesmerized/Toxic-Word-Detection-Project.git
   cd Toxic-word-detection-project
   
2. Create a virtual environment to manage dependencies:
   ```bash
   python -m venv env

3. Activate the virtual environment:

   On Windows:
   ```bash
   .\env\Scripts\activate
   ```
   
   On macOS and Linux:
   ```bash
   source env/bin/activate

4. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   
### Running the Project

5. Start Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook
   ```

   or

   ```bash
   jupyter lab
   
6. Open the project notebook:
   
   Navigate to 'notebooks' directory in the Jupyter interface and open 'Toxic_word_detection.ipynb'.

### Running the Interactive Voilà Interface

7. To run the Voilà interface, ensure you have Voilà installed:
   ```bash
   pip install voila

8. Launch the Voilà interface:
   ```bash
   voila notebooks/TWD_preview.ipynb
   ```
