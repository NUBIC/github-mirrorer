# github-mirrorer

This script automatically mirrors all our organization's public GitHub
repos into a specified directory. It's intended to be used in a cron
job to keep a set of local mirrors up to date for tools that need
local mirrors to work.

## Requirements

* Ruby 1.8.7 (probably 1.9.2+ would work also).

## Usage

    ruby /path/to/github-mirrorer ORG MIRROR_PATH

E.g.:

    ruby /usr/local/bin/github-mirrorer NUBIC /usr/local/share/github-mirror

## Copyright

This script is released into the public domain. Use at your own risk.
