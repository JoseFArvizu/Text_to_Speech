# Text to Speech 📢📝➡️🔊

This Jupyter Notebook provides a simple way to convert text into speech using Python. It can be used to generate audio narration, voice alerts, or accessibility features for applications and documents.

## 📌 Overview

The notebook performs the following:
- Takes a string of text as input
- Converts the text into speech using the `pyttsx3` library
- Saves the audio as an `.mp3` file

## 🚀 Features

- Works offline — no internet connection required
- Fast and lightweight
- Customizable voice rate and voice selection
- Output saved as an audio file (e.g., `output.mp3`)

## 🧰 Requirements

Install the following Python package before running the notebook:

```bash
pip install pyttsx3
```

> Note: On some systems, `pyttsx3` may also require `espeak`, `sapi5`, or `nsss` depending on your OS.

## 🛠️ How to Use

1. Open the notebook `Text_to_Speech.ipynb`.
2. Enter your desired text in the designated input cell.
3. Run all cells.
4. An audio file named `output.mp3` (or your chosen name) will be generated and saved locally.

## 📝 Example

If you input:
```python
text = "Welcome to the Text to Speech demo!"
```

The script will create:
```
output.mp3
```

Which will contain your text read aloud.

## ⚠️ Notes

- Output voice and clarity depend on the text-to-speech engine available on your machine.
- You can modify the speech rate and voice parameters in the script to suit your preferences.
