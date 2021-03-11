# fastread
Simple CLI tool for fast-reading.

## Usage:

    usage: fastread [-h] [-d] [-c N] [-w WPM] [-s N] [--version] FILENAME

    positional arguments:
      FILENAME           Input filename (default: stdin)

    optional arguments:
      -h, --help         show this help message and exit
      -d, --debug        Turn on debug logs
      -c N, --chunk N    Set chunk size to N words
      -w WPM, --wpm WPM  set reading speed (in wpm)
      -s N, --skip N     skip N words
      --version          show program's version number and exit


### Controls:

    j - slow down by 50 wpm
    k - speed up by 50 wpm
    SPACE - pause/resume
    h - [when paused] show previous word
    l - [when paused] show next word
    q - quit
