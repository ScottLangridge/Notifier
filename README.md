# Notifier
A quick class I made for sending push notifications to Android or IOS devices over Pushover.

## Setup
To set this up register for an account with [pushover](https://pushover.net/), then create an API. Both of these processes are pretty 
straight forward. You will be given a user key and an api key. Plug these into the PushoverSender when you initialise it, then sending 
a message is just:

> mySender = PushoverSender(<api_key>, <user_key>)

> mySender.send('This is my message')
