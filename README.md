# Finding_intent_and_entities
In this model in first step I used Wav2Vec to convert given audio file to text, but its accuracy was not that good. So I used
google cloud model for convert given audio file to text but needs credit card so I just copied test from online version.

In next step I created some data to train SVM model to predict Intent of sentences. Then I stored all sentence and intent.

In next step I used spacy library for building model to find Entities also for this model I created data using chatGPT.

in last step I just stored all things in dictionary and converted it into Json file and exported this file.
