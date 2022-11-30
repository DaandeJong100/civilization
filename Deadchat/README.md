# Deadchat command
If you want to make this code work on your own server please read the next paragraph

## Why does this even exist?
I made this command to let specific roles and people ping the deadchat role without allowing everyone to be able to.
This prevents abuse of the system and in combination with the logging mods should be able to keep an eye out on who uses it when and if its being abused.

## $Logging
This command has a built in logging feature which you can use. Please specify what channel id it shouldn't be sent in in this option.

## $deadchat
This is the role ID for your role that you want to ping. 

## Implementing the command itself
If you want to add the command please do the following in the custom command section of the bot dashboard
### `Type:` Command
### `Trigger:` deadchat (or anything you want)

## Usage
**•**`-deadchat` This runs the deadchat ping and also runs the topic command to have something to talk about
<u>**•**`-deadchat [input]` This runs the deadchat ping with the text you specify afterwards</u>