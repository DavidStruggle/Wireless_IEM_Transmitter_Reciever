# Wireless_IEM_Transmitter_Reciever
A very small IEM / Wireless transmitter and reciever based on the TI CC85xx series.

## Introduction
Since wireless IEM systems are pretty expensive, I decided to roll my own based on the TI CC8530 IC. This one comes out at approx 20-25€ per reciever/transmitter (not including the CC-Debugger needed for programming).

The IEM transmitter/reciever is based on the CC85xx headset reference design and packed into a formfactor, that is useful for live concert in ear monitoring. It is designed in such a way, that a standard 18650 battery can fit right next to it and solderd on with taps. 

The board can be programmed to be a reciever or to be a transmitter. All neccessary pins to control the transciever externally are present. This allows you to take full control of all features or further expansion.

## State
Currently, this is the second prototype. The first one already worked fine, but had 2,5mm jacks instead of 3,5mm. The antenna has to be optimized. With the current antenna design, 10 meters seems to be the maximum distance, so there is a lot root for improvement. 

Once I optimized the antenna, I will do a final revision.

## TODO
- Design fitting case for 3D printing
- Improve antenna matching network
- Improve PCB layout
- Finalize schematics and documentation
