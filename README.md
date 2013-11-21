simple-static-server
=============

using express static middleware as a simple static server

## Common usage

when you're developing a client side mvc website(angularJS app) or download a project(h5bp, bootstrap) from github, you can extract it and go to its direcotry, and user `serve` or `server` command to start a
static server and open a browser for you. by default, static-server will use 3000 port, if this port is being used, it will try another automaticly....


## Installing globally:

Installation via `npm`.  If you don't have `npm` yet:

     curl http://npmjs.org/install.sh | sh

Once you have `npm`:

     npm install simple-static-server -g

This will install `simple-static-server` globally so that it may be run from the command line. you will have `serve` and `server` command.

## Usage:

     serve [path] [options]

`[path]` defaults to `./public` or `./app` if the folder exists, and `./` otherwise.

