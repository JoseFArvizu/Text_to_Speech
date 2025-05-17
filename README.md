# Text to Speech 📢📝➡️🔊

This Jupyter Notebook converts input text into speech using the **Google Text-to-Speech (gTTS)** library. It’s useful for generating audio narrations, voice feedback, or adding accessibility features to text content.

## 📌 Overview

The notebook performs the following steps:
- Takes text input from the user
- Converts the text into spoken audio using the Google Text-to-Speech API
- Saves the audio as an `.mp3` file

## 🚀 Features

- Converts any text string into natural-sounding speech
- Simple, beginner-friendly code
- Outputs audio as a `.mp3` file

## 🧰 Requirements

Install the following Python package:

```bash
pip install gTTS
```

> ⚠️ **An active internet connection is required**, as `gTTS` connects to Google's servers for speech synthesis.

## 🛠️ How to Use

1. Open the notebook `Text_to_Speech.ipynb`.
2. Edit the text string you want to convert.
3. Run all cells.
4. The resulting audio will be saved as `output.mp3` (or a filename of your choice).

## 📝 Example

```python
from gtts import gTTS

text = "Hello, this is a text to speech test."
tts = gTTS(text)
tts.save("output.mp3")
```

## ⚠️ Notes

- This notebook uses the **online** Google TTS service.
- For **offline** TTS, you can explore alternatives like `pyttsx3`.
