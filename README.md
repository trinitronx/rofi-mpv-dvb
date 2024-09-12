# rofi-mpv-dvb

Custom script for Rofi to tune `mpv` to a DVB channel via `channels.conf*` file.

## Features

* List all your channels
* Launch `mpv`, tuning to a selected `dvb://` channel

## Installation

1. Make sure you have the requirements installed and available on your `PATH`:
   - [mpv](https://github.com/mpv-player/mpv)
2. Symlink the script to somewhere on your `$PATH`: `ln -s $(pwd)/rofi-mpv-dvb ~/bin/rofi-mpv-dvb`.
3. Run rofi with this as a custom script: `rofi -modi mpv-dvb:rofi-mpv-dvb -show mpv-dvb`

## License

Copyright © 2024 James Cuzella. Code released under [AGPLv3](LICENSE).
