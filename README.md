ff2mpv
======

This is a Firefox addon for playing URLs in MPV.

Clicking the little icon in your toolbar will make MPV attempt to play the current URL.

If you want to play a specific URL on a page, right click it and click the "Play in MPV"
context button.

## Usage

**IMPORTANT**: If you update the addon in your browser, **make sure to update the native host as
well**!

First, install the addon from [AMO](https://addons.mozilla.org/en-US/firefox/addon/ff2mpv/).

Then, copy either `ff2mpv` (the Ruby script) or `ff2mpv.py` (the Python script) to somewhere of your choice. Make sure it's executable.

Finally, copy `ff2mpv.json` (in this repository) into `~/.mozilla/native-messaging-hosts/`. Open
it in your editor, and change the `path` field to correspond to the path where you saved
the script of your choice.

After that, everything should work.

## License

The source code in this repository is licensed under the MIT license.

The icons in this repository are licensed by the MPV team under GNU LGPL, version 2.1.
