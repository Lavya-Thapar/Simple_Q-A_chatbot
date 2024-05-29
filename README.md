**Model**
A nueral network of 5 layers has been used to classify the content into different intents and generate the response accordingly

**Knowlegde Base**
An intents.json file has been prepared having a list of responses according to different intents and acts as a source of knowledge to the chatbot

**Preprocessing**
The WordNetLemmatizer imported from NLTK was used to tokenize the text and make it suitable for training purposes

**Saving**
The trained model was saved to a chatbot_model.h5 file so that it can be loaded into a different file for running

**Working**
The "model", "words" and "classes" were loaded into the running file and the corresponding response gets generated for the user input
