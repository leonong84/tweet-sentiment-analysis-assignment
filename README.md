# tweet-sentiment-analysis-assignment

This project focuses on analyzing the sentiment of short text snippets, akin to tweets, to determine whether the sentiment is positive, neutral, or negative. The core of this analysis lies in leveraging the power of Transformer models, specifically using a variant of RoBERTa that has been fine-tuned on a dataset consisting of tweets.

## Overview

Sentiment analysis is a crucial component in understanding user-generated content on social media platforms like Twitter. The primary goal of this project is to create a robust sentiment analysis model that can accurately interpret the sentiment of a sentence. By utilizing Transformer models, which have revolutionized the way natural language processing tasks are approached, this project aims to provide precise sentiment analysis.

### Model Architecture

The model architecture is based on the RoBERTa (A Robustly Optimized BERT Pretraining Approach) model, which is a variant of BERT that was optimized and fine-tuned specifically for improved performance. Here's the approach taken in this project:

1. **RoBERTa Pre-training:** The base model used is RoBERTa, which has been pre-trained on a large corpus of text to understand the intricacies of language.

2. **Fine-tuning with Tweet Dataset:** The pre-trained RoBERTa model is then fine-tuned further on a dataset consisting of tweets. This step ensures that the model adapts to the language and nuances found in tweets, making it more effective for this specific type of text.

3. **Additional Training:** To further enhance the model's performance, additional training is conducted on another dataset. This step is crucial to refine the model's understanding and improve its accuracy in sentiment analysis.

4. **Model Evaluation:** The model is evaluated using the same dataset at first, then another benchmark set. This is to ensure there is no bias in the performance evaluation process.

5. **Model Tuning:** Different parameters are used for the models to find out the best parameters for the task.

6. **Deployment to Hugging Face:** The final and best model is deployed to Hugging Face, a platform that provides an easy-to-use interface to interact with the model and to integrate it into various applications.

Roberta-tuned-v2 showed the best performance.

https://huggingface.co/leonong84/roberta-base-twitter
https://huggingface.co/leonong84/roberta-tuned
https://huggingface.co/leonong84/roberta-tuned-v2
