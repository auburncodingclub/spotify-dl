# spotify-dl
a script that allows you to download spotify songs or playlists , written in python

This README would normally document whatever steps are necessary to get spotify-dl up and running.

### What is this repository for? ###

* spotify-dl allows you to download spotify songs or playlist
* Version 0.0.1
* This repo contains spotify-dl source code

### Screen ###

![alt text](http://nsa37.casimages.com/img/2016/02/13/160213111903934479.png "spotfy-dl screen")

# How to Install ?
to use spotify-dl , you need to install thoses packages :
  * bs4
  * youtube-dl
  
# MAC OSx
you can use brew to install youtube-dl :
  
    $ brew install youtube-dl
    
and pip to install bs4
  
    $ pip install beautifulsoup4
    
# Linux (debian)
use apt-get install to install youtube-dl

    $ sudo apt-get install youtube-dl
    
and pip to install bs4
  
    $ pip install beautifulsoup4
    
# How to use ?
you can either use your spotify account or downloading single track or playlist by providing an ID , ex:

    $ ./spotify-dl --track {spotify_song_id} --dl youtube
    
this will download the track and save it as mp3 format

you can get the song ID by getting the spotify URI of the song


### Contributors ###

* Hamza Bourrahim
