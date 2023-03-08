# Design-With-Microprocessors-Project

The implementation of a Door Lock System, using a keypad and servo motor, \
and a Face Recognition System which displays the name of the person once detected.

Face recognition:\
This part of the project requires the usage of an ESP-32 Cam module and an FTDI UART module in order \
to work. Once the connection between the camera and the server is established, the project will be able to \
detect the faces of the people facing the camera and, in case the given face matches the pictures stored \
internally, it will display the name of the person, thus signalling that the face has been recognized.

Door lock system:\
This part of the project is a simulation of a smart door that opens if given the correct pin via a keypad. \
The user is first prompted to enter the password and has 3 chances to get it right. If the password is not \
correct, the red led will turn on and the user will be prompted to re-enter it. If the entered password is \
correct, the green led will turn on, and the door will be unlocked using a servo-motor system.
