# flybot
This project is to make chatbot speech according to our voice input.

speech_recog.py code recognises speech and publish text to /voice topic.
chatbot.py code gets the text from the topic feed it to the classifier and publishes the topic in /chat topic.
speech.py code gets the text from /chat topic and converts to speech
intents.json is the model file. Edit it to add more features.
chatgui.py is just a chatbot responds to typing in messages.

