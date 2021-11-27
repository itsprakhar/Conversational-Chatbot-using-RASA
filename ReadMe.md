### Created by Samvram Sahu & Prakhar Thakur 

[IMPORTANT]:
TO train the model run : "rasa train"
Do NOT use rasa train nlu followed by rasa train core (Rasa 2.0 and above apparently have the whole model train option as simply rasa train where you can see in commandline both nlu and core are trained)

The model weights already exist and can be directly run using:
"rasa shell"

Built using Rasa 2.0
Python 3.6

actions/action.py has been modified to include the change of querying from the csv, and sending email. Note sending email is deemed asynchronous and the bot wont crash if the speed of ur internet is good.

data/nlu.yml contains all intents, synonyms etc relevant to our area of study

data/story.yml has been filled with rigorous number of examples from interactive shells which make the bot good
