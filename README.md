# CHATTER
First Chat-bot in Python.
# Prerequisites
pip install tensorflow, keras, pickle, nltk
# How to Make Chatbot in Python?
FILE STRUCTURE-
- Intents.json – The data file which has predefined patterns and responses.
- train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.
- Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
- Classes.pkl – The classes pickle file contains the list of categories.
- Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
- Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.

STEPS
1. Import and load the data file
2. Preprocess data
3. Create training and testing data
4. Build the model
5. Predict the response

# Run the chatbot

We train the model using the command in the terminal- python train_chatbot.py

Then to run the app, we run the second file - python chatgui.py

