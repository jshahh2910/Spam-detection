# Spam Detection

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and supervised learning algorithms.

## Overview

Spam messages are unwanted or fraudulent messages that can clutter inboxes and pose security risks. This project uses text preprocessing, feature extraction, and machine learning models to automatically identify spam messages.

## Features

- Text preprocessing and cleaning
- Tokenization and stopword removal
- TF-IDF Vectorization
- Machine Learning-based classification
- Model evaluation using accuracy and confusion matrix
- Predict custom messages

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- NLTK

## Dataset

This project uses the SMS Spam Collection Dataset containing labeled SMS messages categorized as:

- Spam
- Ham (Not Spam)

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Model Training
6. Model Evaluation
7. Spam Prediction

## Results

The trained model successfully classifies messages as spam or non-spam with high accuracy.

Example:

| Message | Prediction |
|----------|------------|
| Congratulations! You won a free iPhone. Click here now. | Spam |
| Hey, are we still meeting at 5 PM? | Ham |

## Installation

Clone the repository:

```bash
git clone https://github.com/jshahh2910/Spam-detection.git
```

Move into the project directory:

```bash
cd Spam-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python app.py
```

## Future Improvements

- Deploy using Flask or FastAPI
- Build a web interface
- Experiment with Deep Learning models
- Add support for email spam detection

## Author

J Shah

B.Tech Computer Science (AI & ML)

## License

This project is licensed under the MIT License.
