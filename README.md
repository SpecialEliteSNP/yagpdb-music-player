YAGPDB Music Player
================

## This custom command is built to be used with YAGPDB.
This will take the soundboard commands and manipulate them to act like a music player with custom music you upload to the soundboard.

## The main leading command:
`-music <command>` All commands need to be preceeded by this leading command. Where `-` is your server's prefix.

## Current available command actions are as follows:
`play` - Plays a song with the given name  
`playtop` - Adds a song with the given name **ON TOP OF THE QUEUE**  
`playskip` - Skips the current song and plays the song you requested  
`search` - Searches from the Soundboard for a song via your query and returns the top 10 results  
`nowplaying` - Shows what song YAGPDB is currently playing  
`grab` - Saves the current playing song to your Direct Messages  
`replay` - Resets the progress of the current song
`skip` - Votes to skip the current playing song  
`forceskip` - Skips the current playing song immediately  
`stop` - Stops the current playing track  
`resume` - Resumes queued music  
`disconnect` - Disconnects the bot from the voice channel it is in  
`queue` - Shows the first page of the queue  
`shuffle` - Shuffles the entire queue  
`remove` - Removes a certain entry from the queue  
`clear` - Clears the whole queue  

## Commands to be added in the future:
`loopqueue` - Toggles looping for the whole queue  
`move` - Moves a certain song to a chosen (or first) position in the queue  
`skipto` - Skips to a certain position in the queue  
`leavecleanup` - Removes absent user's songs from the queue  
`removedupes` - Removes duplicate songs from the queue
`loop` - Toggles looping for the current playing song  

## Instructions for Setting up
1. Add cc's to custom commands:

  `music.yag` Trigger - Regex: `\A(-\s?|<@!?204255221017214977>\s*)m(usic)?(\s|\z)`. Where `-` is your server's prefix.

  `music2.yag` Trigger - None. (NOTE: Make sure to specify cc # of this in `music.yag` cc)

2. Add songs withing soundboard with following format: `Artist name - Title goes here [3m43s]`
3. Disable `-sb` and `-sbreset` within command overrides in YAGPDB control panel.
4. Enjoy the new Music Player!
