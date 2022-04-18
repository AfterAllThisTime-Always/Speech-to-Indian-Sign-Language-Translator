# Speech-to-Indian-Sign-Language-Translator
A tool to translate Speech (native code supports Hindi, but can be changed for whichever language is required) into Indian Speech Language. The application takes speech as input, converts it into text and then displays appropriate ISL (Indian Speech Language) GIFs or images.

* Speech as input through device's microphone with the help of SpeechRecognition Module.
* Speech Recognition and translation using Google's Speech to Text API and PocketSphinx. The latter module helps in carrying out the tasks even when there is no Internet Connection and Google's Speech to Text API fails to work.
* Text Processing using NLP.
* Front-End using EasyGUI.
* Visual Feedback with the help of Tkinter and Matplotlib modules.
* Not only can this application translate Hindi language into ISL, but it can also translate any language (identified by the Google Speech to Text API) into ISL with a slight change in code. Refer the code for more info on how to do this.

# How to run the Application

1. Clone this repository and then open terminal in the cloned folder.
2. The required libraries have been listed in the Requirements.txt. Write the following command in order to install the necessary packages: `pip install -r Requirements.txt`. All the required packages will have been installed and you will be good to go.
3. Now run the `Speech_Recognition_Hindi.py` file by writing the following command in the terminal: `python Speech_Recognition_Hindi.py`.
4. The application interface appears on the screen.<img width="900" alt="Interface" src="https://user-images.githubusercontent.com/75435809/163868033-d27fc6b4-caa5-488e-ac8f-2a14f7fdadb3.png">

5. Hit the **Speak** button to start taking speech as input.
6. The speech recorded will be translated and relevant GIFs and images will be shown.
7. To exit the whole application, click the **Exit** button present on the interface beside the **Speak** button.

# Objective
This Speech to Sign Language Translator aims at:
* Providing information access and services to deaf people in Indian Sign Language.
* Developing a scalable project which can be extended to capture whole vocabulary of ISL through manual and non-manual signs.

**Sign language is a visual language that is used by deaf people as their mother tongue. Unlike acoustically conveyed sound patterns, sign language uses body language and manual communication to fluidly convey the thoughts of a person. Due to considerable time required in learning the Sign Language, people find it difficult to communicate with these specially abled people, creating a communication gap. Thus, I propose an application which takes in live speech or audio recording as input, converts it into text and displays the relevant Indian Sign Language images or GIFs.**

# For a Better Future for Everyone
![jpg](https://user-images.githubusercontent.com/75435809/163870908-26821726-cb35-44c9-8d5d-99db72cb70ae.jpg)

