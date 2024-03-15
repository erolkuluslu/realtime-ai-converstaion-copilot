### Conversation Copilot

---

#### Overview
The Conversation Copilot is a web application built with Flask, designed to facilitate audio transcription and text generation tasks. It utilizes AWS S3 for audio storage, Replicate for transcription, and MistralAI for text generation. This README provides an overview of the application, its features, and usage instructions.

#### Features
1. **Audio Transcription**: Users can upload audio files through a web interface for transcription.
2. **Text Generation**: The application offers text generation based on user-provided prompts.
3. **Fast Response**: It leverages LLM (Large Language Model) for fast prompt generation and vaibhavs10/incredibly-fast-whisper for rapid text-to-speech conversion, ensuring quick user feedback.

#### Usage
1. **Installation**: Clone the repository and install dependencies using `pip install -r requirements.txt`.
2. **AWS Configuration**: Update `aws_access_key`, `aws_secret_key`, and `bucket_name` with your AWS credentials in the Python script.
3. **Running the Application**: Execute `python app.py` to start the Flask server.
4. **Accessing the Interface**: Open a web browser and navigate to `http://localhost:8080` to access the application interface.
5. **Audio Transcription**: Upload an audio file and click "Start Recording" to initiate transcription. Transcribed text will be displayed.
6. **Text Generation**: Provide a prompt in the text area and click "Get Suggestion" to receive generated text suggestions.

#### Dependencies
- Flask
- boto3
- replicate

#### Acknowledgments
- This application utilizes the capabilities of Replicate for audio transcription and MistralAI for text generation.

#### License
This project is licensed under the [MIT License](LICENSE).

#### Disclaimer
The use of this application may be subject to terms and conditions outlined by AWS, Replicate, and MistralAI. Ensure compliance with their respective usage policies.
