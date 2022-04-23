# NeoBot
## Get your Legal, Tax and Compliance related queries answered.
NeoBot is a python-based chatbot which delivers legal information regarding laws and acts prevailing in our country to the user. 

## Libraries Used:
- nltk
- gTTS
- numpy
- sklearn
- tensorflow
- Flask
- scikit
- os

## Step-wise Procedure:
- Extraction of data from pdf regarding the given acts
- Storing them in the dataset of the chatbot
- Creating detection of keywords and their responses
- Connecting them to the UI

## Features:
1. Response to queries given by the user
2. Detects keywords among the questions asked by the user and respond accordingly.
3. Detects spam/invalid queries and replies accordingly.
4. Has text-to-speech feature for messages given by bot.

## Methodologies Used:
1. Used gpt3, but failed due to deployment issues- could not connect it to the frontend.
2. ChatterBot- gave proper dialogue flow and general conversations but failed during extraction of data from pdf.
3. Used nltk- successfully implemented chatbot with required data. 
4. Used gTTS for text-to-speech responses from the chatbot. 
5. Tried sentiment analysis, but could only get the positive and negative classification on the terminal.

