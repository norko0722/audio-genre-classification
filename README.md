# Audio Genre Classification

Machine learning project for classifying music genre, where user uploads audio file in Web UI and as result will see Music Genre.

## Description

This project implements an audio genre classification system using Python and for Web UI perform JavaScript and Tailwind CSS.
The project focuses on training an AI model to recognize basic music genres. It implements an automated system that extracts key audio features (MFCC, Chroma, Spectral Centroid) using Python and the Librosa library, and classifies audio files into predefined genres with an XGBoost classifier.

## Getting Started

### Dependencies

Before running the project, make sure you have the following installed:

* Python 3.8+
* pip / venv
* Libraries listed in `requirements.txt`

### Installing

1. Clone this repository:
   
   git clone git@github-norko0722:norko0722/audio-genre-classification.git
   cd audio-genre-classification
   
2. Create and activate a virtual environment:
   
   python3 -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows

3. Install dependencies
   
   pip install -r requirements.txt

## Help

If you encounter errors related to missing dependencies, try:
pip install -r requirements.txt --upgrade

## Authors

* Norbert Balucha - @norko0722
