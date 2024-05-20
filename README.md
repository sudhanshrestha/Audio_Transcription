# YouTube Video Transcription Tool

This tool allows you to download YouTube videos as audio files and transcribe them using the Whisper model from OpenAI.

## 🚀 Installation

To use this tool, you need to install the following Python libraries:

```bash
# Libaries to install :
pip install pytube
pip install moviepy
pip install SpeechRecognition
pip install pydub
pip install git+https://github.com/openai/whisper.git

```

## **📝 Usage**

1. Run the script **`audio_to_text.ipynbpy`**.
2. Enter the URL of the YouTube video you want to download when prompted.
3. The audio will be downloaded and transcribed automatically.

## **🛠️ Dependencie**

- [pytube](https://github.com/pytube/pytube): Used for downloading YouTube videos.
- [moviepy](https://github.com/Zulko/moviepy): Used for working with video files.
- [SpeechRecognition](https://github.com/Uberi/speech_recognition): Used for recognizing speech in audio files.
- [pydub](https://github.com/jiaaro/pydub): Used for audio processing.
- [Whisper](https://github.com/openai/whisper): OpenAI's Whisper model for transcribing audio.
- torch
- ffmpeg installed 


## **💡 How it Works**

- The script first downloads the audio from the provided YouTube video URL.
- Then, it transcribes the audio using the Whisper model.
- The transcription result is displayed in the console.

## **📌 Notes**

- Ensure you have ffmpeg installed on your system for video processing.
- Performance may vary depending on the length of the audio and the selected model size.
