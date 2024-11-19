# Text-to-Speech with Sentiment Analysis

## Overview
This project implements a Text-to-Speech (TTS) system using Azure AI services, enhanced with sentiment analysis capabilities. It provides a user-friendly interface built with Gradio, allowing users to generate speech from text with various customization options.

## Features
- Text-to-Speech conversion using Azure AI services
- Sentiment analysis integration
- Customizable speech parameters:
  - Voice selection
  - Speech style
  - Style degree
  - Pitch
  - Speaking rate
- User-friendly interface built with Gradio

## Requirements
- Python 3.x
- Azure AI Services account
- Required Python libraries:
  - azure-cognitiveservices-speech
  - azure-ai-textanalytics
  - gradio

## Setup
1. Clone this repository
2. Install the required dependencies:
   pip install -r requirements.txt
3. Set up your Azure Cognitive Services credentials as environment variables

## Usage
Run the Jupyter notebook `BIAL_TTS_Bot.ipynb` to launch the Gradio interface.

The interface consists of:
1. Input section:
- Text input box for the sentence to be converted to speech
- Dropdowns for selecting voice, speech style, style degree, pitch, and rate
2. Output section:
- Displays the generated speech output

To generate speech:
1. Enter your text in the input box
2. Select your desired options from the dropdowns
3. Click the "Generate Speech" button
4. The synthesized speech will be displayed in the output section

## Contributing
Contributions to improve the project are welcome. Please follow the standard fork-and-pull request workflow.

## Author
Anil Narayanan (anil.narayanan@kyndryl.com)
