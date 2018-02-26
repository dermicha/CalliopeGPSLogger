# Simple Calliope GPS Logger

This litte project was initially developed at #DTHACK2017 (Deutsche Telekom Hackathon Smart Public Life)

## Hardware

* Calliope Mini Board (tested with 2017 version)
* SEEED STUDIO XADOW GPS V2 (about 17€, e.g. at EXP-TEC)
  * http://wiki.seeed.cc/Xadow_GPS_V2/
  * https://github.com/WayenWeng/Xadow_GPS_v2/blob/master/xadow_phone_gps_v2/Sources/gps.h
* Grove cable (just one side with plug needed)

## Software

* PXT Editor (https://pxt.calliope.cc/)
  * mini-SimpleGPS.hex
* Makecode Editor (https://makecode.calliope.cc/)
  * this vesion uses the new function feature, which makes the code more readable
  * mini-SimpleGPS_mcode.hex

## Setup

* check out the project: git clone https://github.com/dermicha/CalliopeGPSLogger.git
* connect GPS Module with Calliope using the left Grove connector
* install 
  * [mini-SimpleGPS](src/mini-SimpleGPS.hex) using [PXT](https://pxt.calliope.cc)
  * or
  * [mini-SimpleGPS_mcode](src/mini-SimpleGPS_mcode.hex) using [MakeCode](https://makecode.calliope.cc)
* open serial console
  * e.g. screen /dev/cu.usbmodem1412 115200

## Feedback

Send any feedback to dermicha (at) dermicha (dot) de

Have fun!
