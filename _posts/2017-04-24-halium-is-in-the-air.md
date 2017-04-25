---
layout: post
title:  "Halium is in the air!"
date:   2017-04-24 10:07:34 +0530
categories: announcements
---

## Preface

Over the years, various efforts have been made to bring GNU/Linux to mobile devices (for example Maemo, Meego, Mer, SailfishOS, Ubuntu Touch, Plasma Mobile). They have either achieved their individual goals or are working in direction of achieving them.

During the development of such projects it was suggested multiple times that these communities should work together as their ultimate goal is the same. However due to various reasons this never happened in the past. However we believe that it is time to change this situation.

## Introducing Project Halium

Currently distributions like AsteroidOS, LuneOS, Mer, Plasma Mobile, SailfishOS, and Ubuntu Touch have one thing in common that they use the libhybris to interact with the android binary blobs and they also run the various android daemons using different methods. And there is lot of fragementation on how this task is handled even though these parts don't need to be different as their essential goal is to make use of android binary blobs.

Project Halium is the effort by the community which aims to bring the common grounds for different distributions and have a common base which includes the Linux kernel, Android Hardware Abstraction Layer, and libhybris. Project Halium also aims to standardize the middlewares used to interact with the hardware of the device. By having these parts shared, we believe that it will reduce the fragmentation we have currently.

## Development Plan

At the time of writing this announcement Project Halium exists merely as a draft document to which multiple developers contributed. However we have come up with development plan or outline which will help you to understand what to expect in the upcoming time.

Initially Halium team wants to work on the proof-of-concept android image which can be reused by more then one distibution. For this we will use the Nexus 5 (hammerhead) as a reference device.

## Why another standard?

From the time community was informed of the project, we were asked the question on why this new effort/standard is needed when there is already xyz distribution and were pointed to this xkcd strip,

![xkcd standards](https://imgs.xkcd.com/comics/standards.png)

However Project Halium wants to see the comic as below,

![xkcd standards final](http://static.davidedmundson.co.uk/blog/standards_final.png)

(Credits to David Edmundson from KDE for this comic)

To explain further, Project Halium doesn't aim to replace any of the phone distributions that are currently available but wants to be part of them. Project Halium is aiming to be the common platform that can be reused by these communites.

More details are documented at the [project planning](https://github.com/Halium/docs/blob/master/Planning.md) page and [development outline](https://github.com/Halium/docs/blob/master/Development.md) page.

## Who are we?

There are many members who contributed to our initial draft document, and some notable mentions are:

- Bhushan Shah
- Marius Gripsgard
- Topias Vainio
- Aleksi Suomalainen
- Lewis Rockliffe
- Michaël Serpieri
- Rohan Garg
- JBB

## Still have questions?

Feel free to join us on our IRC channel at #halium on freenode, or at matrix #halium:matrix.org or on telegram [https://t.me/halium](https://t.me/halium)
