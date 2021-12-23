# ITS_for_visually_impaired
Intelligent Tutoring System(a tutor which can customise teaching based on individual learning abilities) for visually impaired children, which teaches them basic fractional arithmetic using text to speech and voice recognition abilities.

Uses python to teach elementary fractional arithmetic to visually impaired students. 
Facilitates speech to text and text to speech to converse with the user. 
Presents questions to the student based on the previous learning history and capabilities via text-to-speech.
The Student Module  accepts the solution from the user via speech-to-text. Based on the rules 
specified in the Expert Module, it determines the correctness of the solution thus provided. If the 
solution provided by the user is incorrect, it provides customised feedback by interacting with 
the student via the User Interface and helps the student reach the correct answer by prompting 
questions in a step-by-step fashion, moving ahead a step only when the student determines the 
correct answer to the current step. Based on the user’s performance, as determined by the 
errors in the problem solving (or lack thereof), the Tutor Module determines the further course of 
action and tutoring strategies, i.e. whether to revisit the previous concept or go further to the 
next concept based on their relative state on the Expert Module. It assesses whether a 
particular topic has been understood by the student or not.
All the inputs from the student are provided by speech, which is then converted into text for the 
system to understand. Since all the outputs from the system are provided by text, they are 
converted into speech for the target audience to understand better.

IMPLEMENTATION
Process to execute the program(s) with required tools - 
Required Tools: 
-Python (preferably version 3.9 or above)
-PIP(python module manager)
To execute the program first install the following python modules using pip - pyglet, speech_recognition and pyaudio.
After installing the modules execute the following command in the code terminal of the folder:
“python .\user_interface.py”
