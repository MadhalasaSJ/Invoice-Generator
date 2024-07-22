# Invoice Generator Project

### Description

The Invoice Generator is a Streamlit-based application designed to extract and analyze information from invoice images using Google Gemini Pro Vision. The application allows users to upload an invoice image, input a prompt, and receive detailed information based on the image and the provided prompt. This tool leverages the power of Google's generative AI to interpret and provide insights from invoice data, making it a valuable resource for businesses and individuals dealing with invoice management.

### Features
- **Image Upload**: Upload invoice images in JPG, JPEG, or PNG formats.
- **Prompt Input**: Enter specific prompts or questions related to the invoice.
- **AI Response**: Receive detailed, AI-generated responses based on the uploaded invoice and input prompt.
- **Image Display**: View the uploaded invoice image within the application.

### Usage
1. **Install Dependencies**:
   Ensure you have the required libraries installed. You can do this by running:
   ```bash
   pip install streamlit pillow google-generativeai python-dotenv

2. **Environment Setup**:
   Create a .env file in the project directory and add your Google API key:
   ```bash
   GOOGLE_API_KEY=your_google_api_key_here
   
3. **Running the Application**:
   Run the Streamlit application using the command:
   ```bash
   streamlit run app.py


### Requirements
- Python 3.7+
- Streamlit
- Pillow
- Google Generative AI
- Python-dotenv

### Note
Ensure you have a valid Google API key to use the Gemini Pro Vision model for generating responses based on invoice images.



