# replpad

Watches files in specified directory and pipes them to a node repl when ever they change.

Only minor functionality implemented at this point.

Check out this [little screencast](http://youtu.be/rwBuSlzU57Y) to get an idea about what it will do.

## installation

    npm install -g replpad

## usage

    replpad path/to/folder

**Note:** at this point sub directories aren't watched.

## todo

- make sure code is parsable on a line by line basis before sending to repl
- possibly rewrite code in order to fix the above
- remove problematic instructions like hashbang and 'use strict'