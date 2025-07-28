# Twitch Engagement Bot

## Information
This repo allows for a twitch streamer to interact with their twitch chat in such a way that they can provide both keyboard and mouse input remotely. It is fairly minimalistic, but entirely functional. Feel free to add your own commands as you please.

## Notes
As most 3D games use raw mouse input to determine the position to face the player, the look commands are slightly more buggy and will often snap the camera straight down.

# Usage

## Overview
Using this remote access tool requires some minor set up to use, these steps are provided below. Within the twitchConnection.py file, you will need to modify some information to properly connect to the desired channel.

## Requirements
To download the required libraries:

pip install -r requirements.txt

## Steps
**1. Visit https://twitchtokengenerator.com/ and generate a token that has chat:read permissions.**

**2. Set the token as an environment variable with name "TWITCH_OAUTH_TOKEN" and value "oauth:[token]".**

**3. Change [NICK] and [CHANNEL] variables to _your_ channel name.**
