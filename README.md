# Gemini Image Demo: AI-powered Vision Q&A Chatbot

Welcome to the **Gemini Image Demo**! This project is a Q&A chatbot powered by Google's **Gemini-1.5-flash** Generative AI model. It interprets images, specifically invoices, and responds to user queries based on the uploaded image content. The app is built with Streamlit for an interactive, easy-to-use experience.

## Overview

The **Gemini Image Demo** project showcases an innovative approach to document interpretation using AI. By integrating **Google Generative AI** (Gemini) with **Streamlit**, this application allows users to upload an invoice image, input a text-based question, and receive answers extracted directly from the invoice image. This is ideal for use cases like automated invoice processing, financial data extraction, and interactive document-based Q&A.

## Features

- **Intelligent Image Analysis**: Leverages Google's Gemini-1.5-flash model to analyze and understand any image.
- **Text-based Q&A**: Users can ask questions about the uploaded image, and the model provides relevant answers.
- **Simple User Interface**: Built with Streamlit, ensuring an intuitive and interactive experience.
- **Error Handling**: Provides user-friendly error messages if the image is missing or if any issues arise during processing.

## Project Motivation

This project demonstrates my proficiency in:
- **Working with advanced AI models** (Google Generative AI)
- **Deploying interactive web applications** using Streamlit
- **Handling real-world data in image form** and processing it for meaningful insights

## Requirements

Ensure you have the following prerequisites installed:

- Python 3.8 or higher
- Google Generative AI SDK
- Streamlit
- PIL (Python Imaging Library)

Install the required libraries with:

```bash
pip install -r requirements.txt
```

## Setup and Running the Application

1. Clone this repository:

    ```bash
    git clone https://github.com/jddotcom/GEN-AI-Google-Gemini-Text-Extractor.git
    cd GEN-AI-Google-Gemini-Text-Extractor
    ```

2. Set up your environment variables. Create a `.env` file and add your Google API key:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key_here
    ```

3. Run the application:

    ```bash
    streamlit run app.py
    ```

4. Open the local URL provided by Streamlit in your browser to use the app.

## Usage

1. **Enter a Prompt**: This prompt can be a specific question you want the AI to answer based on the uploaded image (e.g., "What is the total amount on this invoice?").
2. **Upload an Invoice Image**: Click "Choose an image..." and upload an invoice image in JPG, JPEG, or PNG format.
3. **Click "Tell me about the image"**: The AI model will analyze the image and provide an answer based on the prompt.

## Code Explanation

### Core Functions

- **get_gemini_response(input_text, image_data, prompt)**: Interacts with the Google Generative AI model, sending it the user’s input, image data, and prompt. Receives and returns the AI’s response.
  
- **input_image_setup(uploaded_file)**: Prepares the uploaded image file by converting it into bytes and formatting it for the model.

### Streamlit Components

- **User Input**: Collects the user's prompt and image file.
- **Response Display**: Shows the AI-generated response or error messages if applicable.

## Demo

*Include a gif or screenshot of the app in action for a better impression.*

## Future Enhancements

- Support for a wider range of documents beyond invoices.
- Enhanced error handling and support for non-English invoices.
- Deployment as a standalone web service for scalability.

## Why This Project is Impressive

This project highlights advanced skills in AI and ML, showcasing the ability to:
- Implement cutting-edge generative AI models.
- Process and extract insights from image data.
- Build interactive applications to enhance user engagement.

## Contact

Feel free to connect with me on [LinkedIn] https://www.linkedin.com/in/jaydeb-das-iimcal/ or check out my other projects on [GitHub](https://github.com/jddotcom).
