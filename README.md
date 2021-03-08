# Rest Chromecast Relay

## Introduction

This is a suite of installation scripts and instructions
that will use two Raspberry Pis to provide an internet
gateway / REST relay to allow control of a Chromecast
device.

The two Pis sit on different networks - the first being
a DMZ which has certain ports opened up to the internet
so that a remote client can issue requests.

The second being the normal internal network.  Note that
no ports need to be opened up for access to the internal
network.

## Pi Image

The Pi installation script places an operating system image
onto the Pi, but also applies an overlay so that when 
running, the memory card is read-only.  This means that 
the risk of corruption on power outages etc. is minimised.

In order to store user data, a USB memory stick is used.
It is essentially used for transient data such as log files.

## DMZ Network

The Pi instance on the DMZ network has two applications
installed on it:

* https web server
* restdmz relay server

## Internal Network

The Pi instance on the internal network has two applications
installed on it:

* restdmz internal server
* chromecast management server

# Installation Instructions

To be added .....




