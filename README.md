# Description:
Fixes local store video produced by the Arlo home security camera.

# Why?
I chose arlo because it offers a local storage option. It allows you to connect a dingus to your home network that will save security video to a hard drive. This is useful because the camera remains functional if my home internet connection goes down.

# What's the Problem?
The video files produced are badly encoded, all with a resolution of 16x32, which do not play in Quicktime. Also they have inscrutible file names, so it's impossible to find a video for a given day and time.

# What does this script do?
It reencodes video files you provide and puts a date & timestamp in the filename.

# Requirements
- ffmpeg
