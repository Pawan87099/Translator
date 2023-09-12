this python code takes voice input from the user and tanslate into spacified language and then playes back the translated text as speech 
break down off code
firstly import necessary python modeules:
1. playsound:- using for playing audio files.
2. speech_recognition:- provide speech recognition functionality, allowing the program to capture voice input.
3. googletrans:- it is use for language translation.
4. gtts:- use to convert text into speech.
5. os:- provide function to interact with operating system.
6. A tuple 'dic' is define to store pair of languages and their respective languages codes.
7. The 'takecommand' function is defined to capture voice input from the using a microphone.
8. The code invokes the 'takecommand' function to get user input and wait for the user to say something.
9. the 'destination_language' function t oget the target language for translation. it continues to prompt the user until a valid language is entered as defined in 
   the 'dic' tuple.
10. ones the sourcetext and target language are determined, the codeuse the 'googletrans' library to translate the source text into target language.
11. The translated text is obtained using 'text_to_translate.text' and then converted into speech using gtts the resulting speech is saved as an audio file named 
   'captured_voice.mp3'.
12. The 'playsound' library is used to play the 'captured_voice.mp3' file, allowing the user to hear the translated text.
13. finally the 'captured_voice.mp3' file is deleted using 'os.remove' to clean up the temporary file.
14. At the end translated text is printed to the console.
15. Example:-
16. input:- how are you
17. output:- आप कैसे हैं
