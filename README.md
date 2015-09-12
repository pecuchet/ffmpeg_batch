# ffmpeg_batch
A bash script to batch convert all .mp4 and .mov videos in a folder at once. It converts to three HTML5 formats, .mp4, .webm and .ogv using ffmpeg.
If the video is wider than 1280px, the script also converts a scaled .mp4 to 1280px for iPhone support.  

(Currently quite basic handling of options and conversion settings.)

## Usage

```ffmpeg_batch ["audio"] [bitrate]```

- ["audio"] default batch does not include audio, type "audio" to allow it
- [bitrate] bit rate defaults to 2000mbps, just provide a higher or lower number