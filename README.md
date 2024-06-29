![final1111](https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/c75668a0-99c6-405b-bca6-059024152c5a)# Medi-Assist
Welcome to the Medi-Assist project! This repository contains the code for a chatbot that utilizes an LSTM (Long Short-Term Memory) neural network, a part of deep learning, for understanding and generating responses, integrated with a Flask web application for an interactive user interface.

Medi-Assist aims to create a conversational AI chatbot that can understand user input and generate appropriate responses using deep learning. The chatbot is trained using an LSTM model on predefined intents, which are sets of patterns and responses. The Flask web application serves as the frontend interface where users can interact with the chatbot.

# Features
•	LSTM Model: Utilizes an LSTM neural network for sequence learning and text classification.
•	Intent-Based Responses: Responds to user inputs based on predefined intents.
•	Interactive Web Interface: Flask web application for user interaction.
•	Team Information Page: Details about the project contributors.
•	Symptoms and FAQ Pages: Lists of symptoms and FAQs for user reference.

# Requirements
•	Python 3.6+
•	TensorFlow 2.x
•	Flask
•	NLTK
•	NumPy
•	scikit-learn

# Working of Chatbot



https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/d7aca39b-9580-448d-8c88-6c7f0fe899ab




https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/25288ba6-f1aa-4897-80b8-dc4f0b588b5a




# Snapshots


![training1](https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/a45e460e-3315-4191-b503-4060d5f1809f)
Chatbot Training


![FAQ](https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/66a17782-b433-471a-a0d0-65a75bfa006a)
Frequently asked questions


![symptoms1](https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/6504dc2a-3c4e-44b9-9935-401bed31688c)
List of symptoms


![symptom2](https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/fadc18b8-9829-476e-8875-bc476411e5d6)
Navigating throughout


![Snapshot](https://github.com/SantraptiNayak/Medi-Assist/assets/107788748/ada44074-7f20-46a1-8597-22c2e057fdf2)
Output



# Installation
1.	Clone the repository:
    git clone https://github.com/SantraptiNayak/Medi-Assist.git cd Medi-Assist 
2.	Install the required packages:
    pip install -r requirements.txt 
3.	Download NLTK data:
    import nltk nltk.download('punkt') nltk.download('wordnet') nltk.download('omw-1.4') 

# Usage
1.	Train the Model:
    python train_chatbot.py 
2.	Run the Flask Application:
    python app.py 
3.	Open your browser and go to http://127.0.0.1:5000/ to interact with the chatbot.

# Project Structure

# Model Training
The model is trained on a dataset of intents defined in intents.json. Each intent includes a tag, patterns, and responses. The LSTM model processes the text data, and after training, the model is saved as chatbot_model.h5.

# Training Script
The training script (train_chatbot.py) performs the following steps:
-> Loads and preprocesses the data.
-> Defines and compiles the LSTM model.
-> Trains the model on the preprocessed data.
-> Saves the trained model and necessary metadata.

# Flask Application
The Flask application (app.py) serves as the web interface for the chatbot. It includes routes for the homepage, team information, symptoms, and FAQs. The chatbot interaction is handled through the /get_response endpoint, which processes user input and returns a response from the trained model.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.



