BiDi support for Weechat using `python-pyfribidi`
================================================
This simple script processes the messages using `fribidi` before they are
printed.  This way you can see messages written in RTL languages like Hebrew
and Arab in the correct order.

This is also allegedly the shortest weechat script that actually does something
useful :)

Dependencies
------------
This script depends on `libfribidi` and it's python bindings. On Debian system
installing this package should be enough:

    # aptitude install python-pyfribidi


TODO
====
- Process the topic lines
- Give a go to the input line

