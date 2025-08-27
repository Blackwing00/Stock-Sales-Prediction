Voice Activated Inventory Assistant
This is a smart inventory assistant that integrates your data with an AI model using Model Context Protocol(MCP).

Description
It uses MCP (Model Context Protocol) to link GPT-style language understanding with structured inventory data and a predictive model. All voice input is processed offline, and the assistant can take actions based on your spoken prompts.

Overview about this Project? To build an offline, voice-enabled analytics tool

To explore GPT4All + inventory Data + predictive modeling integration

To create a smart agent that’s usable in real retail scenarios

Future Improvements

Installation Make sure you have Python 3.8+ installed. Also make sure to install all the docs from the repository.

Place your CSV file:

File: Advertising_Extended.csv

Required columns: TV, Radio, Newspaper, Sales, Stock_Available, Stock_Used, Restock_Threshold, Reorder_Quantity, Stock_Replenished, Date

Run the assistant:

bash Copy Edit python assistant.py

How to Use the Project Open command prompt and enter: uvicorn mains:app --reload to run the fastAPI code Again open the command prompt and enter: streamlit run frontend.py to run the frontend code

You enter the login space. Enter the credentials like this:
<img width="1269" height="671" alt="image" src="https://github.com/user-attachments/assets/546e9d91-c100-4214-b840-8b42775ed5c5" />
