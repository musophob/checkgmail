# TODO

* the script won't exit on it's own. I tried everything from `exit 0` to `exit 1`, but alas it's time for dinner... :( It may be something to do with the `read_xml` function exit status.
* pass a string to be used as a message filter, and only display messages that contain the string. (Is this possible through the atom url, or will it have to be more intricate XML parsing...?)
* prompt user to to open gmail in a browser if mail was displayed (i.e. `open http://gmail.com/`).
* pass a `say` argument to use OSX's `say` command to speak your mail to your (ideally only the From and Subject fields).