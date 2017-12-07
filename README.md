# flac2a
Convert a directory of FLACs to Opus, AAC, or MP3.

Requires [FFMPEG](https://www.ffmpeg.org/) and [GNU Parallel](https://www.gnu.org/software/parallel/). Both of these are probably available from your distro's repositories.

The source file is ```flac2a```, which is a shell script.
```flac2a``` is symlinked to ```flac2opus```, ```flac2aac```, and ```flac2mp3```.

To convert a directory of FLACs:
1. Change into the directory that you want to convert.
2. Run the appropriate command: ```flac2opus```, ```flac2aac```, or ```flac2mp3```.
3. Done.
