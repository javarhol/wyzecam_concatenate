# wyzecam_concatenate
Small command line ffmpeg script to concatenate 60sec .mp4 files from wyze cam

Similar projects:
https://github.com/burns97/WyzeVideoCombiner


## Description 
The [wyze cam v2](https://wyze.com/wyze-cam.html) is an inexpensive surveillance camera that I use to record animal behavior. The benefit is that it comes with great 1080p night vision, wifi streaming, continuous recording on sdcard, and an easy to use interface. However, when recording on the sdcard you will get 60sec videos of every minute you record. So, although you can get 72hr+ of 1080p video on a 32gb sd card, you're left with 4230 videos. But this format does give you great flexibility.

There are at least 3 ways I usually concatenate the video files; 1) 1hr long segments, 2) 24hr long segments, 3) segment out the concatenated video

I usually run the script on WSL for Windows 10 https://docs.microsoft.com/en-us/windows/wsl/install-win10 

But others have used on Mac, expect an update at some point. 

Enjoy.
