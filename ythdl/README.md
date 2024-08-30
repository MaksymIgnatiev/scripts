# YouTube High quality DownLoader (ythdl)

A custom bash script to download videos from YouTube in the highest video and audio qualities. Requires a [yt-dlp](https://github.com/yt-dlp/yt-dlp) and [ffmpeg](https://github.com/FFmpeg/FFmpeg) utillities.  

Examples of usage:  

```sh
# Just download the video from the source to the `video_title.mp4` file
ythdl https://www.youtube.com/watch?v=dQw4w9WgXcQ

# Download the video and safe it as a file with a given name
ythdl https://www.youtube.com/watch?v=dQw4w9WgXcQ someCoolVideo.mp4

# Download the video and safe it to the given directory as a `directory/video_title.mp4` file  
ythdl https://www.youtube.com/watch?v=dQw4w9WgXcQ ~/Downloads/videos

# Force download if the file was already been created, to overwrite it 
ythdl -f https://www.youtube.com/watch?v=dQw4w9WgXcQ someCoolVideo.mp4

# Quite download (without any output)
ythdl -q https://www.youtube.com/watch?v=dQw4w9WgXcQ someCoolVideo.mp4
```

This is a first try, and there may be bugs! So please don't judge too harshly 😅 
