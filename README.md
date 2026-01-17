# Virtual-assistant (Google Colab) – DIO Project
- Project Description

This project implements a Virtual Voice Assistant from scratch using Natural Language Processing (NLP) in Python, designed to run in Google Colab. The assistant can:

Convert speech to text (STT)

Convert text to speech (TTS)

Execute voice commands such as:

Open YouTube

Open Wikipedia

Show nearby pharmacies

The system records audio directly from the browser, converts it to a compatible format, transcribes the speech, and responds with audio feedback.


- Main Features

Voice recording in Google Colab

Text-to-Speech responses (gTTS)

Speech recognition using Google Speech API

Automatic web navigation based on commands

Libraries Used


- Run the following command in Colab before starting:

!pip install SpeechRecognition gTTS wikipedia

Additionally, the project uses:

IPython.display

ffmpeg (for audio conversion)

webbrowser

google.colab.output


- How to Run in Google Colab
Step 1 – Record Audio

Run the cell that creates the “🎤 Gravar 5 segundos” button and speak your command.

Step 2 – Check the recorded audio (optional)
from IPython.display import Audio, display
display(Audio("comando.wav", autoplay=True))
Step 3 – Convert audio to compatible format
!ffmpeg -y -i comando.wav comando_convertido.wav
Step 4 – Run the assistant

Execute the final cell to transcribe your speech and trigger the assistant’s action.


- Available Voice Commands
Spoken Command	Action
“YouTube”	Opens YouTube
“Wikipédia”	Opens Wikipedia
“Farmácia”	Shows nearby pharmacies on Google Maps


- Output Files
File	Description
comando.wav	Raw recorded audio
comando_convertido.wav	Converted audio for recognition
resposta.mp3	Assistant’s spoken response
