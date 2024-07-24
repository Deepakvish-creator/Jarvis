# Jarvis
# AI Voice Assistant Project

This project is based on the YouTube tutorial [J.A.R.V.I.S - OpenAI + Python Powered AI Desktop Assistant that Talks Like a Human (FROM SCRATCH!)](https://www.youtube.com/watch?v=s_8b5iq4Rvk) by Merlin. It demonstrates how to create an AI voice assistant using Python, leveraging OpenAI's language models.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)


## Introduction
Inspired by a YouTube tutorial by Merlin, this project walks through the creation of an AI voice assistant using Python and OpenAI. The assistant can understand and respond to spoken commands, thanks to the integration of speech recognition and natural language processing technologies.

## Features
- **Voice Command Recognition**: Utilizes speech recognition to capture and understand spoken commands.
- **Natural Language Understanding**: Integrates with OpenAI to process and respond to queries in a conversational manner.
- **Task Automation**: Capable of performing various tasks based on voice commands, such as opening websites, playing music, providing the current time, and more.
- **Extensible**: Easily extendable to include more functionalities and integrate with other APIs.

## Requirements
- Python 3.7 or higher
- OpenAI API key
- Additional Python libraries:
  - `speechrecognition`
  - `pyaudio`
  - `openai`
  - `datetime`
  - `os`
  - `subprocess`
  - `wikipedia`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Deepakvish-creator/Jarvis.git
   cd Jarvis
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Ensure you have your OpenAI API key ready.

2. Run the voice assistant script:
   ```bash
   python main.py
   ```

3. Speak your commands into the microphone and let the assistant respond.

## Configuration
To configure the assistant, you may need to:
- Update the API key in the `config.py` file:
  ```python
  OPENAI_API_KEY = 'your_openai_api_key_here'
  ```

- Modify the response handling logic in the `voice_assistant.py` file to customize the assistant's capabilities.


Feel free to modify this template to suit your project's needs and ensure it accurately reflects the content and instructions from the YouTube tutorial you followed.
