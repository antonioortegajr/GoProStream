# GoProStream

Tools for handling/displaying GoPro HTTP/UDP stream. Available in Python.

### Dependencies:

Python3:

* FFMPEG
* urllib

## Screenshots:

![](http://i.imgur.com/5wlh8yS.png) 


## Compatible with:

- HERO3 
- HERO3+
- HERO4
- HERO Session
- HERO+ (incl. LCD)
- HERO5 (needs testing)

## Flags:

    VERBOSE=False

Verbose flag for FFmpeg

    RECORD=False

Sends a record command to the camera, camera must be in video mode!

    SAVE=False

Save the gopro live feed to your machine

    SAVE_FILENAME="goprofeed2"

The filename of the saved video feed

    SAVE_FORMAT="mp4"

File format for saved video feed

    SAVE_LOCATION="/home/konrad/Videos/"

Location for saved video feed (needs to be changed to your username and directory)

### Further instructions:

https://medium.com/@konrad_it/how-to-stream-from-a-gopro-camera-f4a164150797

### Troubleshooting tips
When installing FFMPEG via homebrew be sure FFPLAY gets installed as well.
You might need to use the IP as well as port for the UDP stream.

### Credit

@SonOf8Bits
