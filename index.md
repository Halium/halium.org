---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

# Introduction

Halium is collaborative project which aims to unify the Hardware Abstraction Layer for the different projects who wants to run GNU/Linux on mobile devices with pre-installed Android.

Project Halium will contain,

- Linux kernel (source provided by device vendor)
- Android services required to talk with hardware
- Libhybris

In addition, Project Halium also aims to standardise the middleware software used by various projects to talk with android daemons and make use of hardware, for instance

- OFono/RILd
- Camera service
- Pulseaudio / Audiofingerglue
- GPS
- Media codecs

This project however don't want to control the following higher level parts of stack,

- Display server
- Toolkit
- User interface
- Applications

This is left upon the distribution to decide.
