July 18 2019 








Speech Recoginzation using python 


For file        speech_text.py

pip install SpeechRecognition

https://www.youtube.com/watch?v=K_WbsFrPUCk
https://github.com/umangahuja1/Youtube/blob/master/Python_Extras/speech.py



For file            audio_text.py


https://www.youtube.com/watch?v=l-eD12KDmRc
https://github.com/MauryaRitesh/SpeechRecognition/blob/master/transcribe_audio.py


The audio file should be of any two types mentioned here -  .wav .flag format



Python | Speech recognition on large audio files

https://www.geeksforgeeks.org/python-speech-recognition-on-large-audio-files/

The audio to text py script throws errors for files larger than 10 -20 sec of length as the chuck feed should be small inorder for the google api to translate



In order to process larger audio files we can be Splitting the audio based on silence

Humans pause for a short amount of time between sentences. If we can split the audio file into chunks based on these silences, then we can process the file sentence by sentence and concatenate them to get the result. This approach is more accurate than the previous one because we do not cut sentences in between and the audio chunk will contain the entire sentence without any interruptions. This way, we don’t need to split it into chunks of constant length.

The disadvantage of this method is that it is difficult to determine the lenght of silence to split because different users speak differently and some users might pause for 1 second in between sentences whereas some may pause for just 0.5 seconds.


Libraries required
Pydub: sudo pip3 install pydub
Speech recognition: sudo pip3 install SpeechRecognition