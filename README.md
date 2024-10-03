# Poem Generation Using RNN and GPT-3

## Overview
This project explores the use of Recurrent Neural Networks (RNN) and GPT-3 to generate poems that mimic the styles of various artists. The goal was to combine the rhyme and structure of one artist's style with another artist's lyrics, creating unique poems through machine learning.

## Dataset
- The dataset consists of text files of lyrics and poems by various artists.
- Dataset can be accessed [here](https://www.kaggle.com/code/paultimothymooney/poetry-generator-rnn-markov/input).

## Methodology
1. **Data Preparation**: Text files were processed and tokenized using NLTK. 
2. **Model Training**: RNN with LSTM layers was trained on the lyrics data.
3. **Text Generation**: GPT-3 was used to generate poems that combine the styles of two artists.
4. **User Interface**: A user-friendly interface was built using Gradio.

## Results
The RNN model successfully generated poems, and the GPT-3 model improved the coherence and stylistic consistency of the output.

## Tools and Libraries
- Python: NLTK, TensorFlow, GPT-3 API
- Gradio: For building the user interface
