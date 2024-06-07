Code Warriors 

Problem Statement:
-------------------------
Detection of Footseps and vehicular distance using microphones input for Auditory guidance of visually impaired Individuals

Introduction:
-----------------
We aim to enhance the safety and mobility of the  visually impaired people,by providing real time feedback of an approaching person or a vehicle. 
Procedure:
--------------
We shall first take the  audio input  using microphones and by using factors such as frequency and volume we calculate the distance of approaching footsteps or vehicles.We make sure that all other noises are eliminated leaving them.
We then convert the distance into meters,which are then processed through a text-to-speech convertor,producing a voice output which is fed to the the user through speakers.If the individual happens to be both visually impaired and auditorially impaired,we can send the voice message through brain implants.

Setup:
--------
For this project,we are using python3 Langauge,and Pycharm IDE for using it.We will be taking the help of python libraries such as numpy,scipy,librosa,pyaudio and so on.We will be calculating the distance using frequency of the input audio.For the front end development,we will be using ktinker,and for the text to speech convertor we will be using gtts module.
Regarding hardware requirements,we will be using inbuilt microphones in laptops/mobiles.For mobile usage of the app,we will be using pyqt library.