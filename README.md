# subtitles_merge

subtitles_merge is a GUI application for batch adding subtitle streams to video files. Each video file is processed using the appropriate application for the file type, such as ffmpeg or mkvtoolnix, if it exists on your machine.

## Screenshots
![Main](/screenshots/screenshot_1.png)

Each line in the videos column corresponds to a single .srt file in the subtitles column that will be added to the video as a stream.

![Merge in process](/screenshots/screenshot_2.png)

![Results](/screenshots/screenshot_3.png)

The report screen shows which video files were successful or not, as well as a detailed output showing the result of the underlying commands. 

## Requirements:
* Python 3.6+
* PyQT5
* MkvToolNix (for .mkv files)
* ffmpeg (for .mp4 files)
