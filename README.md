# flac2a
Convert a directory of FLACs to Opus, AAC, MP3, or WAV.

Requires [FFMPEG](https://www.ffmpeg.org/) and [GNU Parallel](https://www.gnu.org/software/parallel/). Both of these are probably available from your distro's repositories.

The source file is ```flac2a```, which is a shell script.
```flac2a``` is symlinked to ```flac2opus```, ```flac2aac```, ```flac2mp3```, ```flac2mp3320```, and ```flac2wav```.

To convert a directory of FLACs:
1. Change into the directory that you want to convert.
2. Run the appropriate command: ```flac2opus```, ```flac2aac```, ```flac2mp3```, ```flac2mp3320```, or ```flac2wav```.
3. Done.

This script is meant as more of a demonstration than a polished tool, but it is still useful.
