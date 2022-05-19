# ChatBot
Chatbot to demonstrate simple machine learning techniques such as natural language processing, tokenization and deep neural network. 

## Steps:

0. Before one starts: 
  - Before you runs the files, make sure you have python and pip installed along with tensorflow, keras, nltk and pickle. Python and pip needs to be installed manually and the other packages can be done with a simple "pip install..." command.
  
```python
pip install tensorflow, keras, pickle, nltk
```

1. Run the train_chatboy.py file:
  - This step will read the intents.json file and pre-process the data with tokenization and lemmatization. It will also create a 3-layer neural network which will be trained with the intents-data. 

2. Start the chatgui.py file:
   - This step will start a simple interactive chatbot which will give a random reply based on the intent-identification from the neural network. 

