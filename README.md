# Ainneve, an example game for Evennia 
| master | develop |
|--------|---------|
| [![Master build Status](https://travis-ci.org/evennia/ainneve.svg?branch=master)](https://travis-ci.org/evennia/ainneve) | [![Develop build Status](https://travis-ci.org/evennia/ainneve.svg?branch=develop)](https://travis-ci.org/evennia/ainneve) |

This branch is a reworking of the original Ainneve project. The goal is to follow closely the new 1.0 tutorial (https://www.evennia.com/docs/1.0-dev/Howto/Howto-Overview.html#the-starting-tutorial), creating a game that a tutorial reader can reference as a more fully developed example. See https://github.com/evennia/ainneve/issues/116 for more background. 

The main configuration file is found in
`server/conf/settings.py` (but you don't need to change it to get
started). If you just created this directory, `cd` to this directory
then initialize a new database using

    evennia migrate

To start the server, `cd` to this directory and run

    evennia -i start

This will start the server so that it logs output to the console. Make
sure to create a superuser when asked. By default you can now connect
to your new game using a MUD client on localhost:4000.  You can also
log into the web client by pointing a browser to
http://localhost:8000.

# Getting started

https://www.evennia.com/docs/latest/index.html

https://www.evennia.com/docs/latest/Tutorials.html

# Contributing

If you're looking for what tasks we need help with, look at our [current open issues](https://github.com/evennia/ainneve/issues).

To let us know you're interested in helping out visit the [Evennia developer IRC](http://webchat.freenode.net/?channels=evennia&uio=MT1mYWxzZSY5PXRydWUmMTE9MTk1JjEyPXRydWUbb) and the [Ainneve](https://groups.google.com/forum/?fromgroups#!categories/evennia/ainneve) category of the mailing list. 

Please submit pull requests as feature branches rather than from your master -- see https://github.com/evennia/evennia/wiki/Version-Control#making-a-work-branch. 


# License

Ainneve uses the BSD license, the [same as Evennia](https://github.com/evennia/evennia/wiki/Licensing).

