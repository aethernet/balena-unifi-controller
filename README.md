# Unifi Controller on balena

This is a very simple block to run Unifi Controller using Balena OS.

As this app will be at the core of your network, you should fork this fleet to run your own.
Using this open fleet for testing and evaluation is fine tho.

# Compatible boards

All ARM64 boards

In practice this has been tested on :

- `Raspberry pi 3`

While it should run on `Raspberry Pi Zero 2`, it currently doesn't install to RAM issue.

The base image this is build on exist for other arch as well (x86-64 and armhf)

Tested on pi0, it works but it's not fast.

Feel free to fork this to run on other arch.

# Documentation

https://docs.linuxserver.io/images/docker-unifi-controller

# Credits

This will run the excellent [`docker-unifi-controller`](https://docs.linuxserver.io/images/docker-unifi-controller) image from https://linuxserver.io
