# SMTIME - Similar Modified Time

Search files with similar modified time. This is usefull to
find files that are related.

For instance, you extracted a tar with a program and want to
remove the binary and all related files.

    rm -i `smtime /usr/local/bin/program /usr/local`

## Prerequisites

+ A POSIX /bin/sh.
+ find.

## Installing

Just copy [bin/smtime](bin/smtime) to the path.

## Help

smtime

    Usage: smtime [-s][-t DIFF] FILE DIR ...
    
    Search files created at similar time as FILE. By default 2 seconds.
    
    -s      : Use `sudo` when searching.
    -t SECS : Change the time window.

## Collaboration

For making bug reports, feature requests and donations visit one of the
following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

