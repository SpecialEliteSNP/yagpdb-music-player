YAGPDB Music Player
================

## This custom command is built to be used with YAGPDB.
This will take the soundboard commands and manipulate them to act like a music player with custom music you upload to the soundboard.

All songs need to be entered manually with their timestamps into this command. All songs and timestamps will be stored in a queue system for the command to pull from.

## The main command:
`-music` The leading command for the music system.

## The command actions are as follows:
**These are to be added after the main command and can be used as a single letter, just like `-music` is the same as `-m`.**

`list` - Provides list of all songs.  
`play <songname>` - Plays a song, or adds it to the queue.  
`queue [songname]` - Shows current queue of songs playing, adding a songname after will queue a specified song (optional).  
`skip` - Skips the current song playing.  
`end` - Stops the music player.  
`clear` - Clears the entire queue.  
`random` - Adds a random song to play.

## Instructions for Setting up
1. Add cc to custom commands. Trigger: Reggex with `\A-m(usic)?(\s|\z)`
2. Add songs withing soundboard with following format: `Artist name - Title goes here [3m43s]`
3. Disable `-sb` and `-sbreset` within command overrides in YAGPDB control panel.
4. Enjoy the new Music Player!