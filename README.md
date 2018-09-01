This is a bash script that will take an mp3 file (or a directory
containing mp3 files) and use sox to compress the audio range,
preserving id3 tags and images.

This is meant to be used on audio which has a high degree of dynamics,
like radio dramas where people shift between shouting and whispering.
It shouldn't be used to compress/normalise music.
