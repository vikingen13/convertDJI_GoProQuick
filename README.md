# convertDJI_GoProQuick
Script based on FFMPEG to modify a DJI video in order to be accepted by GoPro Quick software

##Purpose
GoPro Quick video editing software Automatically turns your footage into killer videos—with themes, music and effects—in just seconds.
Unfortunately, this sofware forbids to import footages captured using another cam, especially a DJI drone.

Our script modify all the DJI videos in a given forlder to make them compatible with the GoPro Quik software.
Note that the script modifies only file headers and do not affect the video or audio quality of the footage.

##usage
./convertDJI [-r|h] folder
options:
h     Print this Help.
r     Remove original files

Note: This script modify DJI*.MP4 in the folder to make them compatible with GoPro Quick software
Files are renamed with a Q appended at the end


