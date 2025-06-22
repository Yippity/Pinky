# Pinky
Feature-rich Discord bot. Developer contact: @yippity on Discord.

Pinky's current features include reaction roles, audio streaming using .wav files, filtering offensive language, bulk deleting messages in a channel, and more. Although Pinky is not currently intended for public use, feel free to take a look at the source code. More information on the developer and how Pinky came to be can be found on GitHub Pages here: https://yippity.github.io/

In order to make the code run, a valid Discord bot token must be encrypted by running aes_handling.py directly. You will need the password you used in order to decrypt it when running the code. The requirements.txt was generated from the configuration used to develop and debug Pinky, and its contents are automatically installed when main.py is run. Finally, the audio streaming would require a "wavs" directory containing valid .wav files, and the language filtering would need various offensive phrases one wants blocked separated by newlines and stored in the currently empty lang_filter.txt file.
