AI-Powered Crop Monitoring Q&A
This project involves training a BERT model to answer questions related to crop monitoring and AI. It includes a Streamlit web interface that allows users to interact with the model. The interface is hosted using ngrok to provide a public URL.

Libraries Used
transformers: For utilizing the BERT model for question answering.
torch: For working with PyTorch, the deep learning framework used in this project.
pandas: For data manipulation and preparation.
re: For text preprocessing using regular expressions.
streamlit: For creating the web interface to interact with the model.
pyngrok: For creating a public URL to access the Streamlit app.
How to Access the Chatbot
The AI-powered crop monitoring Q&A chatbot can be accessed using the following link:

Access the Chatbot

Steps to Run the Project
Set Up the Environment:

Ensure you have a Google Colab account and an ngrok account.
Install Required Libraries:

The following libraries are used in this project:
transformers
torch
streamlit
pyngrok
pandas
re
Train the Model:

Prepare the dataset.
Load the BERT model and tokenizer.
Define the training arguments.
Train the model using the specified dataset.
Create the Streamlit Interface:

Write the Streamlit app to create a user interface for asking questions and displaying answers.
Host the App with ngrok:

Use ngrok to create a public URL that makes the Streamlit app accessible over the internet.
Access the Chatbot
Click on the following link to access the chatbot: 
https://bb86-35-245-14-76.ngrok-free.app/

This link will direct you to the Streamlit interface where you can input your questions related to crop monitoring and AI and get responses from the trained BERT model.
