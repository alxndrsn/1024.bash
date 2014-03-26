1024.bash
=========

Clone of [2048][1] written horribly in bash.


# Known Issues

* seems to be a bug when shuffling and squashing right in the same move, the new tile will disappear << fixed , but probably still occurs going right and up
* need to work out a better way to print numbers - numbers above 2 digits break the layout
* it's really slow!
* loads of copy/pasted code in `shuffle()` and `squeeze()`

# TODO

* check for completing the game
* add scoreboard

[1]: https://github.com/gabrielecirulli/2048

