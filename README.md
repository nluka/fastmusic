# fastmusic

A replacement for the Apple Music app on iPhone.

## Good things about Apple Music app

* Overall layout (of the relevant areas) is pretty good

* Stylish

* Quite reliable, don't remember any crashes or glitches

## Bad things about Apple Music app

* (super annoyance) When changing songs backwards it does this weird buffering and only processes the events after you stop spamming the button, terrible because I can't see what song I'm on as I'm scrolling back, especially terrible when I need to go back a fair way (like 5+ songs)
  * Potential solutions:
    * If the cause is not OS nonsense, then just don't be a dumbass and be a performance aware programming chad
    * If the cause is OS nonsense, then idk

* (medium annoyance) To download music from YouTube, I have to use yt-dlp on a Desktop then transfer via iTunes with a wire
  * Potential solutions:
    * Integrated feature for downloading videos from YT right into the app, leveraging something like libcurl

* (medium annoyance) Can't precisely scrub to timestamp in a long song
  * Solution: add way to jump to precise timestamp

* (medium annoyance) Can't set timestamps/sections in a song
  * Solution: ability to create sections for a song, and have a nice way to see and skip to previous/upcoming sections in a scrollable list ideally from the lock screen

* (medium annoyance) Can't rename a song file
  * Solution: add renaming capability, lol

* (medium annoyance) Can't edit any song metadata (artist, album, genre, etc)
  * Solution: add metadata editor, lol

* (medium annoyance) Bunch of unnecessary menus (I don't care about radio, compilations, etc)
  * Solution: don't include any of this garbage in the app

* (minor annoyance) Can't easily transfer songs to another person's iPhone
  * Solution: feature to send songs to other device (which also has the app) over something like bluetooth

* (minor annoyance) Tedious to delete a lot of songs
  * Solution: add one of those "edit" modes where tapping a song selects it, then issuing the delete command deletes all selected songs

* (minor annoyance) Can't generate a random thumbnail for songs
  * If downloading batch of music like a video game soundtrack where each track is a separate file, then I want to associate a thumbnail to make it visually easier to parse as I'm scrolling through my library
  * Solution: ability to generate a randomized thumbnail and then apply it to songs - ideally in a nice "edit" mode where it can be done efficiently
