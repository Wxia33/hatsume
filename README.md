# Hatsume

Computer vision project for analyzing events in video game clips.  The program analyzes only the content of the video itself, so no naming conventions or metadata are required.

## Description

### Video Organization

Automatically organizes gaming videos into their respective folders.  If you have a bunch of gaming videos in one directory, Hatsume can automatically put the videos in the correct gaming folders.

#### Demo

![](./video_org.gif)

Here, we see a set of videos consisting of 2 black ops, 2 hearthstone, and 1 pubg videos.  All 5 videos are sorted into the correct directories.

### Video Separation

If you have a long recording where you're playing multiple games, Hatsume can split the video where you change between games.

#### Demo

![](./video_sep.gif)

Here, we see the blops_and_hstone file being split into it's respective video games, a video of black ops, and another of hearthstone, which were the two component videos of the original mp4 file.

### Content Highlights (In Progress!)

Highlights sections of your gaming videos where there is a lot of action or something really cool happened.



## Ongoing Work

Classification of video sections that contain interesting action is ongoing.  My ideas for how to get a system working can be found here https://github.com/Wxia33/hatsume-meta

