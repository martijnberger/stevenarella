# Steven (Rust)
[![Build Status](https://travis-ci.org/Thinkofname/steven.svg?branch=master)](https://travis-ci.org/Thinkofname/steven)

A Minecraft client coded in Rust. Ported from [steven-go](https://github.com/Thinkofname/steven-go).
Don't expect it to go anywhere, just doing this for fun.

## Images

![Steven on Hypixel](https://i.imgur.com/PM5fLuu.png)
![Steven](https://i.imgur.com/RRspOQF.png)


In action: http://gfycat.com/NeedyElaborateGypsymoth

## Chat

I generally am on the `irc.spi.gt` irc network in the `#think` channel.
Feel free to pop in to say hi, [Webchat can be found here](https://irc.spi.gt/iris/?channels=think)

## Building
For more detailed info and platform specific instructions check the [wiki](https://github.com/Thinkofname/steven-rust/wiki/Compiling-and-or-running).

Currently requires SDL2, OpenSSL and **nightly** rust to build.

`cargo build --release`

Windows users can download pre-compiled builds from here: https://ci.appveyor.com/project/thinkofdeath/steven-rust/branch/master
(Select your platform, Click the artifacts tab and download Steven.zip)

The Visual Studio 2015 Redistributable is required to run these builds.

## Running

### Standalone

Just running steven via a double click (Windows) or `./steven` (everything else)
will bring up a login screen followed by a server list which you can select a server
from.
