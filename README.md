# Paraphrase-detection
A FLASK-based simple web application for detecting whether two given sentences are pharaphrases of each other. With the help of NLP and Deep learning, the application provides real-time prediction by analyzing the symilarity between the input sentences.

# Table of Contents
1. Features
2. technologies Used
3. File Structure

## Features
- Input two sentences via web-form.
- Real-time paraphrase detection using pre-trained model.
- Flask-based lightweight server response UI.
- JSON response support for API usage.

## Technologies Used
- **Python**: Backend Programming.
- **Flask**: Web Framework.
- **Tensorflow/Keras**: For loading and using the pre-trained deep learning model.
- **NLTK**: Text preprocessing.
- **Scikit-learn**: For TF-IDF vectorization.
- **HTML/CSS**: Frontend UI.

## File Structure

paraphrase-detection/
│
├── app.py                   # Main Flask application
├── detection.ipynb          # main file
├── templates/               # HTML templates for the app
│   └── index.html           # UI for input and results
├── paraphrase_model.h5      # Pre-trained Keras model        
├── tfidf_vectorizer.pkl     # TF-IDF vectorizer
├── questions.csv            # datasets
└── README.md                # Project description


