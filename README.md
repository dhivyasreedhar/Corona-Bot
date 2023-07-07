# Corona-Bot

(Demo link :https://youtu.be/4rib43fSHOU)
## Inspiration
Acting on the wrong information can kill. In the first 3 months of 2020, nearly 6 000 people around the globe were hospitalized because of coronavirus misinformation, recent research suggests. During this period, researchers say at least 800 people may have died due to misinformation related to COVID-19*.

At its extreme, death can be the tragic outcome of what the World Health Organization has termed the infodemic, an overabundance of information  - some accurate, some not  that spreads alongside a disease outbreak. False information runs the gamut, from discrediting the threat of COVID-19 to conspiracy theories that vaccines could alter human DNA.
Preventing false information can :
1. Reduce anxiety and stress among people
2. Reduce the spread of unproven remedies
3. It will prevent people from entering panic mode
4. Prevent contamination of true facts

## What it does
Corona Bot delivers credible and updates information related to COVID 19 regarding the number of cases, recoveries, precautionary measures, and a lot more.
It has :
1. Audio responses and speech recognition. [User commands] 
2.  Choice for male / female voice assistant.
3.  Advanced error handling conditions. 
4.  Mental health support.
5. Includes basic support for North American slang. 
6. Accepts voice commands for a hands-free experience.
7. Accessible to blind and deaf people. [Provides output as both audio and text] 
8. Includes exception handling for personal questions. 
9. Includes the ability to search for off-topic questions. 



## How we built it
Corona Bot is a webscraping project built using python and a few python libraries like speech recognition API's and text-to-speech conversion libraries [pyttsx3]. 

Corona Bot uses an algorithm that was built by us to deliver appropriate responses to each question. It breaks down the user input to separate words and coverts them to lowercase and then matches the word to the keywords from the database. Then based on the tags identified in the user response, the algorithm obtains the latest information through web scraping and delivers customized outputs through the device audio.

## Challenges we ran into
Neither of us had used selenium before so that was a bit tricky. Creating our own algorithm and database gave us a few logical errors. Which we were able to overcome in the end.

## Accomplishments that we're proud of
We are  very proud of successfully creating and implementing my own response generation algorithm and implementing a fully functional exception handling backend.

## What we learned
We learned to do web scraping using selenium and to work with python libraries like pyttsx3 and speech_recogniton.

## What's next for Corona Bot
We want to create a web/ app interface for the corona bot to be easily accessible to everyone.
