# Chatbots and CLU

## Overview
**Chatbots and CLU** is a project focused on creating, managing, and enhancing chatbots with Conversational Language Understanding (CLU). This repository serves as the backend for integrating multiple chatbot frameworks, NLP models, and cloud-based AI services.

## Features
- **Multi-chatbot Integration**: Supports various chatbot frameworks (Google CX, Dialogflow, Rasa, etc.).
- **CLU Implementation**: Seamless integration of conversational AI models for enhanced natural language understanding.
- **Scalable Backend**: Designed for handling multiple chatbot instances across diverse platforms.
- **Cloud Compatibility**: Compatible with AWS, Azure, and GCP for hosting and deployment.

## Usage
1. Clone the repository:

   git clone https://github.com/sourabhbhalke/chatbots-and-CLU.git
   cd chatbots-and-CLU

2. Set up the environment:

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt

3. Run the server:

python app.py


###  Additional Notes
- This chatbot is compatible with GCP Dialogflow CX.
- For users of other platforms (e.g., AWS Lex, Azure Bot Service), manual integration or conversion may be required.




## Tech Stack
- **Backend**: Python, Flask/FastAPI
- **NLP Frameworks**: Rasa, Dialogflow, Spacy
- **Cloud Platforms**: AWS Lambda, Azure Bot Service, Google Cloud Functions
- **Database**: MongoDB, PostgreSQL


## License
This project is licensed under the MIT License.

