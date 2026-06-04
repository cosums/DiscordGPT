# DiscordGPT

A Discord Bot integrated with ChatGPT to chat and also stream YouTube urls. 

## Features

 - Responds to user messages in Discord channels using !chat.
 - Keeps a log of previous conversation history local to each channel.
 - Ability to join discord calls and stream YouTube urls for playback.

## Installation

Clone the repository:

```bash
https://github.com/csummerson/DiscordGPT.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Install [FFMPEG](https://ffmpeg.org/download.html)

## Settings

In settings.toml, input your

- Discord Token
- OpenAI API Key
- Owner ID (to limit use of /destroy)

Also make sure to give the bot

- A status
- Personality prompt

## Running

```bash
py bot.py
```

# History

This was a project originally started in around 2022, when I wanted to try and create something to integrate with AI. After originally trying to make it with C# (my most comfortable language), I later shifted over to python due to better libraries and ease of use. 

This project was retired due to my growing dislike of large AI models and their impact on the environment. While the technology is fascinating and fun to play with, I do not wish to continue supporting the massive LLMs like ChatGPT or Claude. For a more mature version of this project using local LLMs that remain completely on the host machine, see the repo LavaCake.
Of course, local LLMs are still comprised of incomprehensible quantities of stolen data, and still took a massive amount of energy to train. I am sort of... settling for it I suppose. It is not perfectly ethical, but I have taken a step back from the edge.
