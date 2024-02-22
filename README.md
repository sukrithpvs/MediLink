# MediLink

Components:

    Medical Diagnosis and Report Generation Script :
        The first and second code snippets are Python scripts for predicting skin diseases based on input images, generating diagnosis reports, and sending them via email.
        These scripts utilize a pretrained Keras model for skin disease classification.
        Dependencies include TensorFlow, Keras, NumPy, Matplotlib, PIL, and Python libraries for email handling.

    Medical Report Analysis and Query Generation App :
        The third code snippet implements a Streamlit web application for analyzing medical reports, extracting text from images, and generating queries using the Ollama language model.
        It uses PyTesseract for text extraction and the Ollama model for query generation.
        Dependencies include Streamlit, Pillow, pytesseract, and Ollama language model.

    Ollama Medical Model :
        The fourth code snippet is a Streamlit app for interacting with the Ollama language model specifically trained for medical purposes.
        Users can input prompts, and the model generates responses.
        Dependencies include Streamlit and the Ollama language model.

Usage:

    Medical Diagnosis and Report Generation Script:
        Run the script and follow the prompts to input the path to the image, patient information, and email credentials.
        The script predicts skin diseases, generates diagnosis reports, and sends them via email.

    Medical Report Analysis and Query Generation App:
        Upload a medical report image to the web app.
        The app extracts text from the image and generates queries using the Ollama model.

    Ollama Medical Model:
        Interact with the Streamlit app by providing prompts.
        The app uses the Ollama model to generate responses based on the prompts.

Requirements:

    Ensure you have the necessary dependencies installed for each component.
    For the medical diagnosis and report generation script, you need access to a pretrained Keras model and Gmail credentials for email sending functionality.
    The medical report analysis and query generation app require PyTesseract for text extraction and access to the Ollama language model.
    The Ollama medical model app requires the Ollama language model and Streamlit for app development.
