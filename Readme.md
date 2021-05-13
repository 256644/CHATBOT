# INFORMATIVE CHAT BOT

## REQUIREMENTS:
1. Install anaconda 
2. Create conda environment 
   1. open anaconda prompt 
   2. conda create --name nameofenvironment python==3.7.6
   3. conda activate rasa
   4. conda install ujson==2.0.3
   5. conda install tensorflow==2.1.0
   6. pip install rasa==1.10.0
   
## Instructions:

- clone this repository

### Train the model
- > rasa train

### Run the bot 
- > rasa run -m models --enable-api --cors "*" --debug


 - Open index.html file in browser.