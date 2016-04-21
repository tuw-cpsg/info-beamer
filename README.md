About info-beamer
=================

info-beamer allows you to develop interactive information displays using
the Lua programming language. Read more about it on the [main website](http://info-beamer.org/)

Documentation
-------------

The complete documentation is available on [info-beamer.com](https://info-beamer.com/doc/info-beamer)

Installation
------------

Works with [Raspbian](https://www.raspberrypi.org/downloads/raspbian/) from
2016-03-18 (on).

Activate the opengl driver and provide some memory to the GPU with raspi-config.

Install dependencies:

  apt-get install liblua5.1-dev
    libevent-dev libglfw3-dev
    libglew1.5-dev libftgl-dev libavcodec-dev
    libswscale-dev libavformat-dev libdevil-dev
    libxrandr-dev libxi-dev lua5.1

See [installation
information](https://info-beamer.com/doc/info-beamer#opensourceversion) for
more information.