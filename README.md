# MusicalSlayerExciter
Code for an Arduino and Adafruit 128x64 OLED for playing music on a modified slayer exciter circuit. Arrays of notes/note definitions taken from https://github.com/robsoncouto/arduino-songs

# Usage
To use, construct the standard slayer exciter circuit. Attach the emitter of the exciter transistor to the collector of another transistor of the same type. Attach the signal out pin of the Arduino to the base of the second transistor. Finally, attach the emitter of the second transistor to ground. Be sure the circuit and Arduino share a common ground. Simplified circuit diagram can be found at https://www.circuitlab.com/circuit/c4r36pc6sr6z/slayer-exciter/
