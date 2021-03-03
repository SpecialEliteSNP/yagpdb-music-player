YAGPDB Music Player
================

### This custom command is built to be used with YAGPDB.

This will take the soundboard commands and manipulate them to act like a music player with custom music you upload to the soundboard.

All songs need to be entered manually with their timestamps into this command. All songs and timestamps will be stored in a queue system for the command to pull from.

### The main command:

`-music or -m` The leading command for the music system.

### The command arguments are as follows: (add these flags after the leading command)

`list or l` - Provides list of all songs.

`play songname or p songname` - Plays a song, or adds it to the queue.

`queue or q` - Shows current queue of songs playing.

`skip or s` - Skips the current song playing.

`end or e` - Stops the music player.

`clear or c` - Clears the entire queue.

`random or r` - Adds a random song to play.

### Instructions for Setting up

1. Add cc to custom commands.

2. Add songs withing soundboard with following format: `Artist name - Title goes here [223]` 223 = seconds

3. Disable `-sb` and `-sbreset` within command overrides in YAGPDB control panel.

4. Enjoy the new Music Player!
