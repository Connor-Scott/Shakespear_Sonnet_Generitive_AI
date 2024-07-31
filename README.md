# Shakespear Sonnet Generator 

## Introduction
This is a generative AI model trained on all of Shakespeare’s sonnets. Sonnets provided ideal training material for the model because of their uniform structure. The model 

## Features
Classical Sonnet Generation: Produces sonnets with adherence to traditional structures and themes.
Stylistic Diversity: Trained on a diverse corpus of sonnets to capture a wide range of poetic styles.
Saved Model: File containing the trained model is included, both as a .keras file and the legacy .h5 file. 

## LSTM Model Architecture
The LSTM model consists of two Bidirectional LSTM layers, two dropout layers, and a dense output layer to predict the next characters in the line of the sonnet. 

## Dataset
The model was trained on "Shakespeare's Sonnets” collected from Project Gutenberg. Shakespeare Sonnets were chosen because of their uniform text structure, unique stye, and availability. 
