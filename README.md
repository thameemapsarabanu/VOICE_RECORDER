# voice_recorder
The given code is a voice recorder application built using the tkinter library in Python. When executed, it creates a GUI window with the title "Voice Recorder" and a logo image at the top. The user can enter the duration of the recording in seconds through an entry box.

Upon clicking the "Record" button, the application starts a countdown timer based on the entered duration. The timer is displayed on a label in the GUI. Once the timer reaches zero, a message box appears indicating that the time is up.

During the recording, the application captures audio using the sounddevice library and saves it as a WAV file named "recording.wav". The audio is sampled at a frequency of 44100 Hz with 2 channels (stereo).

Overall, this code provides a basic interface for recording audio using the computer's microphone and saving it as a WAV file.
