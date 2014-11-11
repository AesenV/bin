~/bin
=====
Random sometimes-useful scripts from Aesen's ~/bin.

What they do 
============
ytrip
-----
`ytrip <youtube-url> <outfile>`  
Example: `ytrip http://www.youtube.com/watch?v=dQw4w9WgXcQ AmazingSong.ogg`  
Dependencies:
 * curl
 * livestreamer
 * jq
 * ffmpeg
 * vorbisgain

Downloads a video from YouTube, converting it on the fly to Ogg Vorbis and saving it to a file. It then runs vorbisgain on the result to add ReplayGain information.

get-mcserver
------------
`get-mcserver <version> <outfile>`  
Example: `get-mcserver 1.7.10 minecraft_server.jar`  
Dependencies:
 * curl

Downloads an arbitrary version of the vanilla Minecraft server to the given file.

parallel
--------
`parallel <command-list>`  
Example: `parallel compress-logs`  

Runs a list of commands in parallel, up to 7 at a time.

mvnsum
------
`mvnsum <file>`  
Example: `mvnsum lwjgl-2.9.1.jar`  
Dependencies:
 * md5sum
 * sha1sum
 * awk

Creates two Maven-style checksum files in the same directory as the passed file.

install-prompt
--------------
`install-prompt`  

Installs my custom prompt. It looks pretty.  
![Screenshot of the prompt](http://i.imgur.com/WrfOXCP.png)
