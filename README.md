# bitwave_chat_listener
A read only chat client so you can listen to chat and provides basic processing features for messages

## Setup
`pip3 install python-socketio colorama pyttsx3`

or `pip install python-socketio colorama pyttsx3`

if you are still living in python2.0 land for some reason

## Usage

To use chat reader
`./readchat`

or if it's not marked as executable

`python3 readchat`

you can also create the files users, channels, and tts

Creating the `tts` file will enable tts

Adding one user name per line in the `users` file will ignore them.

Adding one channel name per line in the `channels` file will ignore them.

`readAllAlerts` is used to forced the reading of all alerts, if set to false it will only read and display alerts on the channel set to for: `listen_channel`

Alerts are also colored in the window and has the color read preceeding the message.