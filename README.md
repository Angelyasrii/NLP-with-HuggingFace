# NLP Pipelines with Hugging Face Transformers

This repository demonstrates the use of various Natural Language Processing (NLP) tasks implemented using the Hugging Face transformers library. The code leverages pre-trained models for multiple NLP applications, including text classification, generation, sentiment analysis, named entity recognition (NER), and more. 

## Overview

This project utilizes 10 different NLP pipelines, each performing a specific task with minimal configuration. Below is a summary of the tasks and their corresponding pipelines.

## Pipelines Used

1. *Zero-Shot Classification*
   - *Description*: Classifies text into predefined labels without the need for training a model specifically for the task.
   - *Example*: Classifying a text about Artificial Intelligence into categories like AI, machine learning, robotics, and data science.

2. *Text Generation*
   - *Description*: Generates continuation of a given text based on an initial prompt.
   - *Example*: Generating a continuation of the sentence "Throughout this journey, we’ll guide you to."

3. *Text Generation with DistilGPT-2*
   - *Description*: Similar to the previous text generation pipeline, but using a lighter model, DistilGPT-2, for faster and more efficient text generation.
   - *Example*: Generating two text sequences from the prompt "This journey will transform you into."

4. *Fill-Mask*
   - *Description*: Predicts the word to fill in the <mask> placeholder in a given text.
   - *Example*: Filling in the blank in the sentence "This course will transform you into an <mask> master."

5. *Named Entity Recognition (NER)*
   - *Description*: Identifies and categorizes entities such as people, locations, and organizations in a given text.
   - *Example*: Extracting named entities like "Angel" (person) and "Infinite Learning" (organization) from a sentence.

6. *Question Answering*
   - *Description*: Answers a question based on a provided context or passage of text.
   - *Example*: Answering the question "Apa itu Machine Learning?" based on the provided context about Machine Learning.

7. *Sentiment Analysis*
   - *Description*: Analyzes the sentiment (positive, negative, or neutral) expressed in a given text.
   - *Example*: Analyzing the sentiment of a text about Artificial Intelligence and its impact on industries.

8. *Summarization*
   - *Description*: Summarizes a long text into a shorter version, preserving key information.
   - *Example*: Summarizing an article about Indonesia’s socio-economic changes in recent decades.

9. *Translation (Indonesian to English)*
   - *Description*: Translates text from Indonesian to English using a pre-trained translation model.
   - *Example*: Translating "Saya sangat membenci durian karena baunya sangat tidak enak" from Indonesian to English.

10. *Question Answering with Different Context*
    - *Description*: Similar to the previous question answering pipeline, but used with different contextual information.
    - *Example*: Answering the question "Apa itu Universitas Negeri Padang?" based on a given context about the university.

## Requirements

- Python 3.6+
- transformers library (install via pip install transformers)
