# Arty-A7-100-Pmod-I2S2
Created for Vivado 2017.4

This project demonstrates the use of the Pmod I2S2 with the Arty A7-100, by creating a passthrough data stream from Line in to Line Out. The volume of the audio can be adjusted by changing the switch positions. All switches up represents the original volume of the input stream, while all switches down represents mute. Other positions represent a fractional volume, M/15 of the original volume, where M is the state of the switches, encoded in binary.

This demo can be built and programmed onto an Arty A7-100 by following the [Using Digilent Github Demo Projects](https://reference.digilentinc.com/learn/programmable-logic/tutorials/github-demos/start) tutorial.

While following the tutorial above, keep in mind that this demo is an HDL-only project, and does not use Vivado SDK.

A Pmod I2S2 (FIXME store link), headphones, and an audio source are required to run this demo, before programming the bitfile onto the board, make sure to plug the Pmod I2S2 into Pmod port JA and to connect audio input and output devices to the Pmod I2S2's 3.5mm jacks.
