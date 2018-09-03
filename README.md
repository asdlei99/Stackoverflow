# Stackoverflow
All source codes I've provided on stackoverflow as an answer, usually under tags ms-media-foundation.

## CustomVideoMixer
This program shows the basic essentials for implementing a custom video mixer, to be used by a media session.

In this example, I use two identical mp4 files, big_buck_bunny_240p_5mb.mp4 and a copy of itself. the two videos use NV12 video format as input. therefore, there is no real alpha mix, but both videos can be displayed next to each other, as the picture below.

![Custom Video Mixer](./Image/CustomVideoMixer.jpg)

## TranscodeMp4ToMp4
This program transcode a mp4 video file into a new mp4 file. There is no real encoding process, because output file has the same format as input file.
The concept was to show how to setup IMFTopologyNode for both audio and video.
