# Twitch Engagement Bot

## Information
This bot allows a Twitch streamer or viewer to listen to a livestream, transcribe short segments of audio, and use a language model to send contextually relevant and characterful responses in chat. It's ideal for interacting as a personality or character during streams, or simply to allow a Twitch streamer with minimal viewership to practice their communication skills within a controlled environment.

You can use this bot within any Twitch channel. The period in which the bot waits between messages and the length of audio recorded can be customised to meet your own desire.

## Features
- Records short clips (default: 15 seconds) from any Twitch stream.
- Transcribes audio using OpenAI Whisper.
- Produces output via Google Gemini (Gemini 1.5 Flash model).
- Identity of engagement bot can be customised to meet your own desire.

## Notes
- If the bot fails to transcribe a segment of audio of sufficient the length, it will assume nothing was said and repeat the loop.
- Recorded audio will temporarily be saved within the audio.mp3 file.
- Transcribed audio will temporarily be saved within the transcript.txt file.

# Usage

## Requirements
To download the required libraries:
pip install -r requirements.txt

## Steps
**1. Visit https://twitchtokengenerator.com/ and generate a token that has both chat:read and chat:editpermissions.**

**2. Set the token as an environment variable with name "TWITCH_OAUTH_TOKEN" and value "oauth:[token]".**

**3. Change [NICK] and [CHANNEL] variables to _your_ channel name.**
