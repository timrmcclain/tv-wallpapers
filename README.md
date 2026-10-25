# tv-wallpapers

The photo list my living room TV follows.

`wallpaper-feed.txt` is read by the TV's launcher once a day. One line per photo:
the image's https address, a TAB, then the caption shown on screen.
Lines starting with `#` are ignored.

Edit this file and the TV catches up within 24 hours: new lines are downloaded,
removed lines are deleted from the TV. If the file can't be reached, the TV keeps
showing whatever it already has.

Images must be jpg, png or webp, served over https, and under 10 MB each.
At most 100 are used.

The starter set is landscape photography from Wikimedia Commons; each caption
carries its photographer and licence.
