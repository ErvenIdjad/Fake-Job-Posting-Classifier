# 🔍 Fraud Detection in Job Postings using NLP and Machine Learning

## Overview 📖

This project leverages Natural Language Processing (NLP) and Machine Learning to detect fraudulent job postings. The system processes job posting data, extracts relevant features, and classifies the postings as either fraudulent or legitimate.

![image](https://github.com/ervenderr/Fraud-Detection-in-Job-Postings-using-NLP-and-Machine-Learning/assets/81071981/ac160a5c-e21a-493b-92a9-fb2176b739e2)


## ⚙️ Tech Stack

- Python
- Jupyter Notebook
- Flask
- HTML/CSS
- scikit-learn
- pandas
- nltk

## Features ✨

- **Data Preprocessing**: Cleans and preprocesses job posting data for analysis.
- **Feature Extraction**: Utilizes NLP techniques to extract features from text data.
- **Model Training**: Implements machine learning algorithms to classify job postings.
- **Web Interface**: Provides a user-friendly interface for interacting with the classifier.

## Requirements 🛠️

- Python 3.7+
- Jupyter Notebook
- Flask

## Installation 📦

1. Clone the repository:
    ```sh
    git clone https://github.com/ervenderr/Fraud-Detection-in-Job-Postings-using-NLP-and-Machine-Learning.git
    cd Fraud-Detection-in-Job-Postings-using-NLP-and-Machine-Learning
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Download the `nltk` data:
    ```python
    import nltk
    nltk.download('all')
    ```

4. Run the Jupyter notebook to preprocess the data and train the model:
    ```sh
    jupyter notebook jupyter/preprocess_and_train.ipynb
    ```

## Usage 🚀

1. **Run the Flask application**:
    ```sh
    python app.py
    ```

2. **Access the web interface**:
    - Open your browser and go to `http://localhost:5000`.

3. **Classify Job Postings**:
    - Use the web interface to input job postings and receive classification results.

## File Structure 🗂️

- `app.py`: Flask application script.
- `jupyter/`: Jupyter notebooks for data preprocessing and model training.
- `static/`: Static assets like CSS and images.
- `templates/`: HTML templates for the web interface.
- `model.py`: Script for building and evaluating the machine learning model.
- `requirements.txt`: List of required Python packages.

## Contributing 🤝

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## Acknowledgments 🙏

- Thanks to all contributors and open-source libraries used in this project.
