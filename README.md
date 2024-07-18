# Business-AI-Meeting-Companion-STT
Introduction
Consider you're attending a business meeting where all conversations are being captured by an advanced AI application. This application not only transcribes the discussions with high accuracy but also provides a concise summary of the meeting, emphasizing the key points and decisions made.

In our project, we'll use OpenAI's Whisper to transform speech into text. Next, we'll use IBM Watson's AI to summarize and find key points. We'll make an app with Hugging Face Gradio as the user interface.


# Preparing the environment
Let's start with setting up the environment by creating a Python virtual environment and installing the required libraries, using the following commands in the terminal:

>> pip3 install virtualenv


>> virtualenv my_env
>
>
>>source my_env/bin/activate # activate my_env
>>
>>
Then, install the required libraries in the environment:
# installing required libraries in my_env
>> pip install transformers==4.35.2 torch==2.1.1 gradio==4.17.0 langchain==0.0.343 ibm_watson_machine_learning==1.0.335 huggingface-hub==0.19.4


# We need to install ffmpeg to be able to work with audio files in python.


>> sudo apt update

>>sudo apt install ffmpeg -y
