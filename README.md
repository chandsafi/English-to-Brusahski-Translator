# English-to-Brusahski-Translator


The English-to-Burushaski Translator is a machine translation project designed to facilitate communication and understanding by translating English text into the Burushaski language. This project aims to bridge the gap between English speakers and the Burushaski-speaking community through AI-driven solutions.

Features

Translation from English to Burushaski

Word-to-word translation support

Utilizes a LSTM Model.

Custom dataset created specifically for the Burushaski language

Motivation

Burushaski is a lesser-documented language, and there are limited resources available for machine translation. This project is a step towards creating digital tools for language preservation and fostering communication for the Burushaski-speaking community.

Dataset

The dataset used for this project includes:

English sentences paired with their Burushaski translations

Data manually curated and stored in an Excel format

Model Architecture

The translation model employs:

LSTM

Encoder-decoder framework for efficient language modeling

Preprocessing techniques to tokenize and pad the input sentences

Technologies Used

Python

TensorFlow/Keras for building the neural network

Pandas and NumPy for data manipulation

Jupyter Notebook for development and experimentation

Installation

To run this project locally:

Clone the repository:

git clone https://github.com/username/english-to-burushaski-translator.git

Navigate to the project directory:

cd english-to-burushaski-translator

Install the required dependencies:

pip install -r requirements.txt

Usage

Load the dataset into the project folder.

Train the model by running the train_model.py script.

python train_model.py

Test the translation by running the translate.py script with an English sentence:

python translate.py "Enter your English sentence here"

Results

The translator is capable of translating basic sentences with reasonable accuracy. Work is ongoing to improve translation quality by enhancing the dataset and refining the model architecture.
