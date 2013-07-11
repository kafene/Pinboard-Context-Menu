# Pinboard Context Menu

Add Bookmarks to Pinboard.in from the context menu (right click).

This is an Add-On (aka Extension) for the new Opera web browser based on Chromium.
It may also be compatible with other Chromium-based browsers, however it has only
been tested in Opera.

## Development Notes:

Using chrome.window.create() was working okay, except that Pinboard's call
to window.close() was being forbidden, but window.open() seems to allow for it.

I also wanted to allow a way to bookmark a link when it's under the mouse
cursor, but there seems to be no easy way to get the title of the link to
feed it to Pinboard, so I gave up on that feature for now.

## About:

The icons are from [http://simpleicons.org](Simple Icons by Dan Leech),
Licensed under the [Free Art License](http://artlibre.org/licence/lal/en).  
GitHub Link: <https://github.com/danleech/simple-icons>

This extension is not officially sponsored or endorsed by Pinboard.in.
