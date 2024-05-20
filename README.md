# mera-chatboat
Develop an interactive chatboard for a food website to manage orders: place, track, add, remove, and complete orders efficiently.



#1.
=================
The project involves creating an interactive chatboard for a food website using Dialogflow. This chatboard manages nine food items, enabling users to place, track, add, remove, and complete orders seamlessly through a conversational interface. Dialogflow's natural language processing capabilities ensure smooth, intuitive interactions, making the ordering process efficient and user-friendly.

#2.
Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code
#3.
Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"
#4
To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

#5
ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.




