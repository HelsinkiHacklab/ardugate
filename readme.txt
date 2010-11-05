Contains sources for:

An IRCbot written in Java
- sits on an irc channel and communicates with arduino over an usb serial connection
- forwards commands from irc to the arduino, and messages from arduino to irc

A host program for the arduino
- communicates with the java program over usb serial
- receives commands and handles them
- sends messages to irc through the java program e.g. when the pir sensor is triggered (after a cooldown period)

