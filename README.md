# ffmpeg_batch
A bash script to batch convert all .mp4 and .mov videos in a folder at once. It converts all HTML5 formats (mp4, webm, ogv) using ffmpeg.
(Currently quite basic handling of options and conversion settings.)

## Usage

```ffmpeg_batch ["audio"] [bitrate]```

- "audio" default batch does not include audio, type "audio" to allow it
- bit rate defaults to 2000mbps, just provide a higher or lower number