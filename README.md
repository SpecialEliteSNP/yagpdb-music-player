YAGPDB Music Player
================

### This custom command is built to be used with YAGPDB.

This will take the soundboard commands and manipulate them to act like a music player with custom music you upload to the soundboard.

All songs need to be entered manually with their timestamps into this command. All songs and timestamps will be stored in a queue system for the command to pull from.

### The commands you can use are as follows:

`-play songname`

`-shuffle`

`-skip`

`-songlist`

`-off`

### Instructions for Setting up

1. Add list of all songs from Soundboard in the following format:

```"Songname1" "03m04s"
   "Songname2" "02m15s"
   .
   .
   .
   "SongnameX" "04m30s"
```

2. Change CC in trigger to new handler CC no.

4. Disable `-sb` and `-sbreset` within command overrides in YAGPDB control panel.

6. Enjoy the new Music Player!
