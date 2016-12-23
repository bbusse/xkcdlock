# xkcdlock
A wrapper around screen lockers to display xkcd images

Depending on the given arguments xkcdlock shows a random image, the latest
image or an image of choice.

Note that 'latest' needs an internet connection for the download!
If the download fails it falls back to a specific hard-coded image

Builtin is a function to download all images.

Dependencies: rbash, i3lock, xrandr, awk, curl,
              convert (from imagick)

Use 'xkcdlock -h' to show the command help.

In order to use the xkcd font for the image number overlay,
you need to download it from here: https://github.com/ipython/xkcd-font
and put the xkcd.otf in your font path, e.g. /usr/share/fonts
