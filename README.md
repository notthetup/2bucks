# 2bucks 💰
A simple PCB with 2 DCDC (buck) regulators

## Description

This PCB solves the requirement for having 2 low-power lower voltage power rails generated from a higher voltage (usually 24V) rails for testing small project. Instead of sticking multiple small DC-DC modules which makes cabling a mess, I thought it would be simpler to make a quick PCB.

The PCB is designed to be as small as possible, and I also forgot to add any mounting holes. **Oops!**

It uses screw termnials for input and output It currently targets the [MornSun SIP DC-DC modules](https://www.mornsun-power.com/html/products/1987/regulated-output--0.5-3a.html), but it can be easily used with other 3-pin SIP DC-DC modules.

I originally created this in [EasyEDA](https://easyeda.com/) just to see how easy it is, but I am trying to moving to KiCad. I have included the EasyEDA files in the [easyeda folder](/easyeda/), and the original is [published at oshwlab](https://oshwlab.com/chinpen/2-bucks_copy)

I also played with paneling of the PCBs using [JLCPCB](https://jlcpcb.com/) to see how they come out.

## Images

![PCB](/imgs/schematic.png)

![PCB](/imgs/layout.png)

![3D](/imgs/3d.png)