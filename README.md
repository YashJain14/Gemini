# Gradio UI for Gemini-Pro-Vision

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/YashJain14/Gemini
    ```

2. Install the required dependencies:

    ```bash
    pip install gradio google-generativeai pillow
    ```

3. Set up your Google API key:

    - Obtain an API key from [Google AI Studio](https://ai.google.dev/).
    - Set the API key as an environment variable:

        ```bash
        GOOGLE_API_KEY="API_KEY_HERE"
        ```

## Usage

1. Run the `multimodal.py` script:

    ```bash
    python multimodal.py
    ```

2. Access the application via the provided URL (typically http://127.0.0.1:7860/) in your web browser.

3. Use the chat interface to interact with the generative models:

    - Enter text in the text box and press Enter, or upload an image by clicking on the image box.
    - Click the Submit button to send the input to the generative models.
    - View the responses generated by the models in the chat interface.

## Components

### Generative Models

- **Text Model (`gemini-pro`):** This model generates text based on the input text provided by the user.
- **Vision Model (`gemini-pro-vision`):** This model generates text based on both the input text and the input image provided by the user.

### Gradio Components

- **Chatbot:** Displays the conversation between the user and the generative models.
- **Textbox:** Allows the user to enter text inputs.
- **Image:** Allows the user to upload image inputs.
- **Button:** Triggers the submission of user inputs to the generative models.



