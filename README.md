## anki-remote

A command line interface for querying and managing Anki's user interface remotely.

### Installation

*Ubuntu*

1. Install my fork of [anki-connect](https://github.com/glutanimate/anki-connect/tree/gui-controls) and restart Anki
2. Clone this repository
3. Install `python-requests`, e.g. via `sudo apt install python-requests`

*Other platforms*

1. Install python and pip, e.g. with `sudo apt install python python-pip`.
2. Install my fork of [anki-connect](https://github.com/glutanimate/anki-connect/tree/gui-controls) and restart Anki
3. Clone this repository
4. Run `pip install -r requirements.txt` in the project root directory

### Usage

Launching the add cards window:

    ./anki-remote -a

Launching the card browser:
    
    ./anki-remote -b

Performing a search:

    ./anki-remote -b "osteoporosis"

Run with `-h` for more details on other options.


### Credits and License

*anki-remote* is *Copyright © 2017 [Aristotelis P.](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl.html).

This script would not not have been possible without the following open-source projects:

- [ankicli](https://github.com/davidshepherd7/ankicli) by [David Shepherd](https://github.com/davidshepherd7). Licensed under the GNU AGPLv3.
- [AnkiConnect](https://github.com/FooSoft/anki-connect). Copyright (c) 2016 [Alex Yatskov](https://github.com/FooSoft). Licensed under the GNU GPL.

