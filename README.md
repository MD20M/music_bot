# Music bot by MD20M
This music bot allowes the users to play the sound of any youtube video in a discord voice channel.

# CURENTLY UNDER MAINTENANCE


## Installation
First you need to install some dependencies:
```js
$ npm install --savevdiscord.js
$ npm install --save discord-player
$ npm install --save @discord-player/extractor
$ npm install --save ffmpeg
```

Next download/copy the [index.js][index.js] and [config.json][] files.

[index.js]: https://github.com/MD20M/music_bot/blob/main/index.js
[config.json]: https://github.com/MD20M/music_bot/blob/main/config.json

After that change the word TOKEN in the config.json into your Discord bot token

## Startup
To start up the bot you have to run the index.js file using:
```js
node index.js
```

## Usage
First type `!deploy` in a discord channel. After that you should see slash commands appear.

### Play a song
To play a song use the `/play` slash command. In the field `query` either type the song name or the youtube video link.

### Skip a song
To skip a song use the `/skip` slash command.

### See the queue
To see the song queue use the `/queue` slash command.

### Stop the music from playing
To stop the music from playing use the `/stop` slash command.

## FAQ
1. - Q: Does the bot work on replit?
   - A: No replit doesn't support ffmpeg anymore
   
2. - Q: Will there be any new updates to the bot?
   - A: I do not plan on upgrading the bot

3. - Q: Where can I host the bot?
   - A: On your PC or any discord bot/code hosting service
