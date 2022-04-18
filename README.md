# Speech-to-Indian-Sign-Language-Translator
A tool to translate Speech (native code supports Hindi, but can be changed for whichever language is required) into Indian Speech Language. The application takes speech as input, converts it into text and then displays appropriate ISL (Indian Speech Language) GIFs or images.

* Speech as input through device's microphone with the help of SpeechRecognition Module.
* Speech Recognition and translation using Google's Speech to Text API and PocketSphinx. The latter module helps in carrying out the tasks when there is no Internet Connection and Google's Speech to Text API fails to work.
* Text Processing using NLP.
* Front-End using EasyGUI.
* Visual Feedback with the help of Tkinter and Matplotlib modules.

# How to run the Application

1. Clone this repository and then open terminal in the Master directory.
2. The required libraries have been listed in the Requirements.txt. Write the following command in order to install the necessary packages: `pip install -r Requirements.txt`. All the required packages will have been installed and you will be good to go.
3. Now run the `Speech_Recognition_Hindi.py` file by writing the following command in the terminal: `python Speech_Recognition_Hindi.py`.
