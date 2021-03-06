#Shooter-Serial-Control

[![Join the chat at https://gitter.im/FRC1716/Shooter-Serial-Control](https://badges.gitter.im/FRC1716/Shooter-Serial-Control.svg)](https://gitter.im/FRC1716/Shooter-Serial-Control?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Shooter-Serial-Control controls the two-cylinder, four-relay pneumatic loading and firing system via a serial connection.

##Input
Input is solely numerical. Certain numbers 1 through 9 activate different actions.

##Feedback
Various punctuation marks are placed in feedback.
A '..' after feedback indicates that the action stated will complete promptly.
A '...' before feedback indicates that the action stated follows an automatic action.
A '...' after feedback indicates that an automatic action will follow the stated action.
A '!!' after feedback indicates that no action was performed.

##Troubleshooting
If the Arduino is not responding to commands, ensure that Newline is enabled in the serial connection.
