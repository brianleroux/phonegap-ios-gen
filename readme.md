phonegap-ios-gen
===

cmd line utilities for common phonegap/ios tasks; orig prototyped in cordova and now on their way to phonegap/ios

reqs
---

1. ios sdk
2. ios-sim
3. phonegap/iphone

usage
---

start with the followin steve jobs inspired command:

    ./bin/BOOM

it should create a phoengap/iphone project in the root called `./example`, compile it, launch it in the sim and attach a logger to stout.

from there you could play w/ the other scripts:

    ./bin/BOOM ......................... play with the example app
    ./bin/create [path package name] ... creates a phonegap/iphone project
    ./bin/debug [path name] ............ compile app and launch in the sim
    ./bin/emulate ...................... launch the ios simulator
    ./bin/log [path] ................... console.log to stdout

feedback and bugs appreciated!
