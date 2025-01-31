speech-to-Text and Language Translation Application

This project is a simple voice translator that allows users to speak in one language and get the translation in another language. The translated text is also converted into speech and saved as an audio file. The project uses Python libraries for speech recognition, translation, and text-to-speech conversion.

Features:-
Speech Recognition: Captures voice input and converts it into text.

Language Detection: Detects the language of the recognized text.

Translation: Translates the recognized text into the target language.

Text-to-Speech: Converts the translated text into speech and saves it as an audio file.

Prerequisites
Before running the project, ensure you have the following installed:

Python 3.10 or higher version

Required Python libraries (listed in requirements.txt)

Installation
Clone the repository:

bash
Copy
git clone https://github.com/your-username/voice-translator.git
cd voice-translator
Install the required libraries:

bash
Copy
pip install -r requirements.txt
Usage
Run the script:

bash
Copy
python trans.py
Enter the target language:

When prompted, enter the target language (e.g., 'Hindi', 'Telugu', 'Tamil', etc.).

You can also enter the language code directly (e.g., 'hi', 'te', 'ta', etc.).

Speak when prompted:

The program will prompt you to speak. Speak clearly into the microphone.

The recognized text will be displayed, and the program will detect the language of the spoken text.

View the translation:

The program will translate the recognized text into the target language and display the translated text.

Listen to the translated text:

The translated text will be converted into speech and saved as an audio file in the outputs folder.

The audio file will be played automatically.

Supported Languages
The following languages are supported for translation:

Hindi (hi)

Telugu (te)

Kannada (kn)

Tamil (ta)

Malayalam (ml)

Bengali (bn)

English (en)

You can add more languages by extending the language_map dictionary in the trans.py script.

Project Structure
trans.py: The main script that handles speech recognition, translation, and text-to-speech conversion.

requirements.txt: Lists the required Python libraries for the project.

outputs/: Directory where the generated audio files are saved.

Dependencies
SpeechRecognition: For capturing and recognizing speech.

googletrans: For translating text.(googletrans==4.0.0-rc1)

gtts: For converting text to speech.

#SpeechRecognition
#googletrans==4.0.0-rc1
#gtts


Troubleshooting
Speech Recognition Issues:

Ensure that your microphone is working properly.

Speak clearly and reduce background noise.

If the speech recognition fails, try running the script again.

Translation Issues:

Ensure that you have a stable internet connection, as the translation service requires an internet connection.

If the translation fails, check if the target language is supported.

Text-to-Speech Issues:

Ensure that the gtts library is installed correctly.

If the audio file is not played automatically, check the file path and try playing it manually.

Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

