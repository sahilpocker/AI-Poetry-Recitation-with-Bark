# AI-Poetry-Recitation-with-Bark
This project is a creative endeavor that combines text generation, text-to-speech conversion, and poetry recitation. It utilizes the Bark TTS library to convert generated poems into speech. The generated audio is split into lines due to a 14-second limit on audio generation and then concatenated to create a complete recitation. The project is designed to run on a Google Colab notebook.

## Getting Started
To get started with this project, follow these steps:

Open the Poetry_Recitation_Using_Bark.ipynb notebook in Google Colab.

Make sure you have access to the necessary APIs and libraries. You can install Bark TTS library using the following command if it's not already installed:

Replace the variable topic with the desired poem topic. The notebook will generate a poem based on the specified topic.

Follow the notebook instructions to generate and concatenate the audio for the poem.

## Demo

To provide a quick demonstration of this project, two sample poems are included in the repository with the following prompts:
 1) AI and the Future
 2) The Obstacles in Life

## To-Do
Here are some future enhancements that can be made to this project:

1. Create a GUI for Easy Interaction
Implement a graphical user interface (GUI) that allows users to input the poem topic and receive the final audio output. This will make the project more user-friendly and accessible.

2. Train with External Voices
Train the text-to-speech model with external voices that have appropriate intonation for poetry recitation. These voices can be sourced from other poem recitals or recordings, ensuring that the generated audio is more expressive and engaging.

## Dependencies
The project relies on the following libraries and APIs:

Bark TTS Library
Pytorch
Text generation API (e.g., ChatGPT or another)

## Disclaimer
Please note that this project is intended solely for research and educational purposes. Ensure that you use this project responsibly and in compliance with all relevant laws and regulations. The generated content, especially when using text generation APIs, may vary in quality and should not be used for any harmful, unethical, or malicious purposes. Respect copyright and intellectual property rights when generating and sharing content.
