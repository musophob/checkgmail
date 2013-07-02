# checkgmail

## About

checkgmail is a simple bash script that parses a [gmail's atom XML feed](https://mail.google.com/mail/feed/atom) and reports back with a preview of messages in your inbox. It's mostly a way to look cool and hackerish while still doing something productive. Anyone who lives by the prompt may also find it useful as a non-obtrusive, [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done)-compliant way to quickly scan your inbox


## Installation

1. drop the `checkgmail` executable somewhere in your $PATH
2. `chmod +x ./checkgmail`


## Usage

1. fire up a terminal and type `checkgmail`
2. enter your username and password
3. read your mail
4. exit, and decide if it's worth typing `open "http://gmail.com/"`
5. have a nice cup of tea and reflect


## Customise It

1. enter your username directly in the `wget` command and delete the lines asking for `$USER`
2. do the same for $PASS, if you dare.
3. maybe even alias `checkgmail` to something like `cg`


