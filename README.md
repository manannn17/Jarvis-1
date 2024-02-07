# Jarvis-1

Readme:

Description:

Speech Recognition and Text-to-Speech Conversion:

The program uses the speech_recognition library to recognize speech input from the user. It utilizes the pyttsx3 library for text-to-speech conversion to provide audible responses. Voice Commands:

The assistant listens for specific voice commands, such as "time" for fetching the current time, and "who is" for getting information about a person from Wikipedia. When a command is recognized, the assistant responds accordingly with the requested information. Integration with External APIs:

For playing songs, the program uses the pywhatkit library, which interacts with the YouTube API to play songs. For retrieving information about a person, it utilizes the wikipedia library to fetch a summary from Wikipedia. Continuous Loop:

The program runs in an infinite loop, continuously listening for voice commands and responding to them. It prints the recognized commands and responses to the console for debugging purposes. Error Handling:

Basic error handling is implemented to catch exceptions during speech recognition and API calls.
