# Archive

Any further development has been transfered to [torge](https://github.com/TUVIMEN/torge).

# t1337x

A shell script for searching torrents on 1337x.

![example](example.gif)

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)
 - xclip

## Installation

    install -m 755 t1337x /usr/bin

## Usage

Just type 't1337x your search', choose what you want and the magnet link will be copied to your clipboard.

Search for the biggest linux isos

    t1337x -s size linux iso

Search for the smallest linux isos on second page

    t1337x -r -s size -p 2 linux iso

Search different domain for linux isos and change delimiter to space

    t1337x -D ' ' -d 'https://otherdomain.to' 'linux iso'

Get some help

    t1337x -h
