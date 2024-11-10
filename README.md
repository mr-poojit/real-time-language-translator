# Real-Time Multilingual Speech Translation System

This project provides a real-time speech-to-speech translation system in multiple languages. It captures English speech from a microphone, translates it into a set of target languages, and plays the translated text as audio. This can be useful for language learning, communication across language barriers, or real-time translation needs.

## Features
- Captures speech input via microphone (English by default).
- Translates the recognized speech into multiple languages.
- Plays the translated text as audio in each target language.

## Target Languages
Currently, the system supports translation to the following languages:
- Spanish (`es`)
- French (`fr`)
- German (`de`)
- Kannada (`kn`)
- Hindi (`hi`)
- Telugu (`te`)
- Marathi (`mr`)

You can easily add more languages by updating the `target_languages` list with the desired ISO 639-1 codes.

## Requirements

Install the required libraries:

```bash
pip install SpeechRecognition googletrans==4.0.0-rc1 gTTS
