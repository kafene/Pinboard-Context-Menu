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

## License:

```
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```

For more information, please refer to <http://unlicense.org/>
