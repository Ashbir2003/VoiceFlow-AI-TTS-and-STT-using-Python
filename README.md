# VoiceFlow AI – Text to Speech and Speech to Text using Python

 Project Overview
VoiceFlow AI is a simple Python project that demonstrates how speech processing works.
It converts **text into speech (Text-to-Speech)** and then converts that **speech back into text (Speech-to-Text).
This project helps beginners understand how voice-based AI systems work using Python libraries.

 Features
* Convert text into an MP3 audio file
* Convert MP3 audio into WAV format
* Perform speech recognition to convert audio back into text
* Demonstrates the basic workflow used in voice assistants

 Technologies Used

* Python
* gTTS (Google Text-to-Speech)
* SpeechRecognition
* pydub

 Project Workflow

1. Input text is provided by the user.
2. The gTTS library converts the text into an MP3 audio file.
3. The MP3 file is converted into WAV format using **pydub**.
4. The SpeechRecognition library processes the audio.
5. The speech is converted back into text.

Installation
Install the required libraries:

pip install speechrecognition
pip install gTTS
pip install pydub

How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells sequentially.
3. The program will:
   * Generate an MP3 audio file from text.
   * Convert it to WAV format.
   * Recognize the speech and output text.

 Example
Input Text:
Hello, this is a sample mp3
Generated Output:
* Audio file: `output.mp3`
* Recognized Text:
Hello, this is a sample mp3

Learning Outcome
* Basics of speech processing
* Text-to-Speech (TTS)
* Speech-to-Text (STT)
* Audio format conversion

