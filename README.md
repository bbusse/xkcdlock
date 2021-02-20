# xkcdlock
A wrapper around screen lockers to display xkcd images  
Currently supported are i3lock and swaylack

Depending on the given arguments xkcdlock shows a random image, the latest
image or an image of choice.

Note that 'latest' needs an internet connection for the download  
If the download fails it falls back to a specific hard-coded image

Builtin is a function to download all images.

## Dependencies
rbash, xrandr, awk, curl, convert (from imagick)

## Usage
Use ```xkcdlock -h``` to show the command help
