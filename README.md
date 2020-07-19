# MysticScripts
Scripts for use with Mystic BBS

## Status, as of July 19th, 2020:
### Usable items:
####stormcalendar.mpy
Displays a daily ANSI, given a directory full of ANSIs with a particular naming scheme. Aimed at being a, "today's holiday" sort of item. ANSIs are in /stormcal

####lightning.mpy
Does five short flashes of lightning using yellow and black. Works pretty well, and is seen on Storm BBS as an interstitial in a couple of spots.

### Experimental items:
####aprilpy.mpy
Contains earlier/different version of lightning, an earlier version of gogame, a "count to n" function, and a function that goes through various Mystic BBS commands, one after another. It's all very experimental, though the different version of lightning is interesting

####gogame.mpy
It... mostly works. It's possible to play a game, challenge a person, go back and forth on moves, replay some example games... And if things go outside of a certain path, it'll go haywire very quickly. The code is a mess, and needs a rewrite where I think it through from the beginning, in order to separate out as much as possible (and make things able to be unit tested). I'll still consider it a success, though, as it was useful in teaching me some Python basics as well as some basics about what Mystic BBS can do. Requires GoMill.

