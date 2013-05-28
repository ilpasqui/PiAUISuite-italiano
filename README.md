<h4>VERSIONE IN ITALIANO (WORK IN PROGRESS) - Credits to Steven Hickson</h4>
<h1>
Raspberry PI - controllo vocale (con google speech API)
</h1>
Permette di controllare tramite comandi vocali il Raspberry PI, utilizza il motore google speech in italiano


Alternative User Interface
Includes voicecommand, download, playvideo, and textcommand scripts

this Requires boost, curl, xterm, espeak, and some other things
If you don't have dependencies installed (you may need to find a different version of boost)
try running sudo apt-get install libboost1.50-dev libboost-regex1.50-dev youtube-dl axel curl xterm libcurl4-gnutls-dev mpg123 flac sox

To install:
cd Install; ./InstallAUISuite.sh

It will ask you if you want to install the dependencies and then will ask to install each script.

playvideo:
    Uses a special locate database and omxplayer to quickly locate and play videos.
    http://stevenhickson.blogspot.com/2013/03/playing-videos-intelligently-with.html

downloader:
    Uses curl and transmission to find the best torrent based on your input and then starts downloading it.
    http://stevenhickson.blogspot.com/2013/03/automatically-downloading-torrents-with.html

gtextcommand:
    Uses curl and my google voice api in order to make the computer check for text messages every minute and run a command that you send.
    http://stevenhickson.blogspot.com/2013/03/controlling-raspberry-pi-via-text.html

youtube:
    Uses youtube-dl and other scripts to play youtube files.
    http://stevenhickson.blogspot.com/2013/04/using-youtube-on-raspberry-pi-without.html

voicecommand:
    Uses googles api and a special config to run commands based on what you say.
    http://stevenhickson.blogspot.com/2013/04/voice-control-on-raspberry-pi.html

Copyright 
GPLv3
Steven Hickson
