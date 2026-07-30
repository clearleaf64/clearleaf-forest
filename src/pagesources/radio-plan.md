
# Radio plan

This site uses no server at all, it's just static pre-generated files that get downloaded. 

1. The page contains a javascript applet that will fetch a playlist file from IPNS. This playlist file is a jason array where each line contains a time of day over a 24 hour period (synced to UTC), followed by a track title, artist, and other metadata, and then an IPFS hash pointing to a raw audio file. 
2. The applet will check the current UTC time and then see which song should be playing, and how far into the song it should be. 
3. The applet will then play the song from that point in the file. 
4. When the song is half over, the next song is downloaded and the previous song is deleted. 