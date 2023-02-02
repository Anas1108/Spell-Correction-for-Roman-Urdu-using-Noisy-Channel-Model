# Spell Correction for Roman Urdu using Noisy Channel Model

## Introduction
This project aims to develop a spell correction system for Roman Urdu using the Noisy Channel model, which is based on Bayes Theorem. The spell correction system consists of four main components:
1. Language Model: A statistical model that represents the distribution of words in a language and assigns probabilities to sequences of words.
2. Error Model: A statistical model that represents the distribution of errors made by users when typing text, and assigns probabilities to sequences of incorrect words given a sequence of correct words.
3. Candidate Words Generation: A component that generates a list of candidate words for a given incorrect word, based on a dictionary of correct words and some heuristics.
4. Selection Model: A component that selects the most likely correct word for a given incorrect word based on the probabilities assigned by the Language Model and the Error Model.

## Requirements
To run this project, the following software and packages are required:
* Python 3.x
* spaCy
* Numpy
* Pandas

## Usage
The steps to develop a spell correction system for Roman Urdu using the Noisy Channel model can be summarized as follows:
1. Clone the repository containing the code and data.
2. Install the required packages such as spaCy, Numpy and Pandas.
3. Train the Language Model and Error Model on a large corpus of text. This involves estimating the probabilities of sequences of words and errors.
4. Implement the Candidate Words Generation component, which generates a list of candidate words for a given incorrect word based on a dictionary of correct words and some heuristics.
5. Implement the Selection Model, which selects the most likely correct word for a given incorrect word based on the probabilities assigned by the Language Model and the Error Model.
6. Test the spell correction system on a large test set of text to evaluate its performance.

## Conclusion
This project provides a general overview of how to develop a spell correction system for Roman Urdu using the Noisy Channel model. The spell correction system you will be developing will be able to correct spelling errors in Roman Urdu text with a high degree of accuracy, based on the probabilities assigned by the Language Model and the Error Model. The code and data for this project can be easily adapted and modified to develop spell correction systems for other languages or to use different text processing and spelling correction techniques.
