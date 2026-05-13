Project Overview
This project involves building a retrieval-based AI Chatbot using Natural Language Processing (NLP) and Deep Learning. The chatbot is designed to understand user intents from a JSON-defined dataset and provide contextually relevant responses. It utilizes a Neural Network to classify user queries into predefined categories (tags) like greetings, help, name, and status.

Technical Stack
Language: Python

Deep Learning: TensorFlow / Keras

NLP Toolkit: NLTK (Tokenization & Lemmatization)

Data Handling: NumPy, JSON, Pickle

Model Architecture: Feed-forward Neural Network (Sequential)

Key Features
Intent Classification: Categorizes user input using a trained Neural Network.

Text Preprocessing: Implements tokenization and lemmatization to handle various word forms.

Early Stopping: Optimized training process to prevent overfitting.

Threshold Filtering: Ensures the bot only responds when confidence is above 60%.

Project Deliverables
Chatbot.ipynb: The complete source code for training and inference.

intents.json: The dataset containing patterns and responses for various intents.

chatbot_model.h5: The saved trained model weights.

words.pkl & classes.pkl: Serialized preprocessing data for consistent inference.

Model Performance
Based on the training logs, the model achieved:

Accuracy: 100.00% (1.0000)

Loss: Extremely low (approx. 0.0077)

Demo
The chatbot successfully responds to queries such as:

User: "Hello" -> Zak-Bot: "Hi there!"

User: "Who are you?" -> Zak-Bot: "I am Zak-Bot, your AI assistant."

User: "How are you?" -> Zak-Bot: "I'm doing well, thanks!"
