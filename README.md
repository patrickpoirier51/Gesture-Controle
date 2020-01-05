# Gesture-Controle
Use AI based Gestures to Control a Quadcopter (or others) using Mavlink RC-OVERRIDE commands

We use PoseNet models that are quantized and optimized for use on Coral's Edge TPU USB Stick on a RaspBerry Pi 4.

https://github.com/google-coral/project-posenet

The script rc_control.py is based on the synthesizer.py example as we use position of the hands to 
create 4 values corresponding to the RC Channels.

The RC channels are scaled to the correct output so it can be used to override the rc values of a Mavlink controlled vehicle

This script is still WIP

